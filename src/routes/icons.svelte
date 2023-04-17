<script>
    import { onMount } from 'svelte'
    import querystring from 'query-string';
    import moment from 'moment'
    export let videoId;
    let contentDetails,
        player,videoPlayer,statistics,snippet,
        tags = [], 
        title,
        publishedAt,
        viewCount;
    const endpoint = 'https://www.googleapis.com/youtube/v3/videos',
        args = {
            id: videoId,
            part: 'snippet,player,statistics',
            maxResults : 1,
            key : API_KEY
        }
    onMount( async () => {
        let response = await fetch(`${endpoint}?${querystring.stringify(args)}`);
            response = await response.json()
            const { items } = response;
            let { snippet, contentDetails, player, statistics } = items[0];
            videoPlayer = player.embedHtml;
            title = snippet.title;
            tags = snippet.tags;
            viewCount = statistics.viewCount;
            publishedAt = moment(snippet.publishedAt).format("DD MMM YYYY");
    });
    const numberWithCommas = x => {
        return x && x.replace(/(\d)(?=(\d{3})+(?!\d))/g,'$1.')
    }
</script>

<div id="video">
    <div id="video-player">
        {@html videoPlayer }
    </div>
    <div class="tags">
        <ul>
            {#each tags as tag}
                <li>#{tag}</li>
            {/each}
        </ul>
    </div>
    <h1>{ title }</h1>
    <p><span class="views">{numberWithCommas(viewCount)} visualizzazioni</span> &bull; <span class="publishDate">{publishedAt}</span></p>
</div>

<style>
    #video {
        border-bottom: 1px solid rgba(0,0,0,.1);
        margin-bottom: 20px;
        padding-bottom: 20px;
    }
    #video-player {
        position: relative;
        padding-bottom: 56.25%;
        height: 0;
        margin-bottom: 20px;
    }
    #video-player > :global(iframe) {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
    h1 {
        font-size: 18px;
        font-weight: 400;
        margin: 0 0 10px;
        padding: 0;
        line-height: 1;
    }
    .tags,.tags ul {
        margin: 0;
        padding: 0;
    }
    .tags ul li {
        color: rgb(6, 95, 212);
        font-size: 12px;
        font-weight: 400;
        display: inline-block;
        margin-right: 4px;
    }
    p {
        color: rgb(96,96,96);
        font-size: 14px;
        font-weight: 400;
    }
</style>