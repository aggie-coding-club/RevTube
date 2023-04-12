<script>
	import '../routes/styles.css';
	import MdAccessTime from 'svelte-icons/md/MdAccessTime.svelte';
  import MdShare from 'svelte-icons/md/MdShare.svelte';
	
    
    function viewVideo() {
        alert("link video");
    }

    function showOptions() {
        // 
    }

    // // dropdown menu
    // document.querySelector('.dropdown-toggle').addEventListener('click', function() {
    // document.querySelector('.dropdown-menu').classList.toggle('show');
    // });

    // // hide dropdown menu
    // window.addEventListener('click', function(event) {
    // if (!event.target.matches('.dropdown-toggle')) {
    //     var dropdowns = document.getElementsByClassName('dropdown-menu');
    //     for (var i = 0; i < dropdowns.length; i++) {
    //     var openDropdown = dropdowns[i];
    //     if (openDropdown.classList.contains('show')) {
    //         openDropdown.classList.remove('show');
    //     }
    //     }
    // }
    // });
</script>

<div class="videoicons">	

	<div class="video-container">
        <div class="thumbnail-container">
          <img src="">
          <div class="timestamp">06:49</div>
        </div>
        <div class="info-container">
          <div class="profile-pic">
            <img src="">
          </div>
          <div class="video-info">
            <div class="video-title">Video Title</div>
            <div class="profile-name">Profile Name</div>
          </div>

          <div class="dropdown">
            <button class="dropdown-toggle">&#8942;</button>
            <div class="dropdown-menu">
                <a href="#">
                    <div class="options">
                        <div class="icon"><MdAccessTime/></div>
                        <span>Watch Later</span>
                    </div>
                </a>
                <a href="#">
                    <div class="options">
                        <div class="icon"><MdShare/></div>
                        <span>Share</span>
                    </div>
                </a>
                <a href="#">
                    <div class="options">
                        <div class="icon"><MdAccessTime/></div>
                        <span>Option 3</span>
                    </div>
                </a>
                <a href="#">Option 2</a> 
            </div>
          </div>
      </div>
    </div>

    <div class="video-container">
      <div class="thumbnail-container">
        <img src="https://media.gq.com/photos/62323a83863acf184ea0f791/16:9/w_1280,c_limit/160322_Drake_HP.jpg">
        <div class="timestamp">06:49</div>
      </div>
      <div class="info-container">
        <div class="profile-pic">
          <img src="data:image/jpeg;base64,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">
        </div>
        <div class="video-info">
          <div class="video-title">21 did sum for mey</div>
          <div class="profile-name">KanyeWestLover96</div>
        </div>

        <div class="dropdown">
          <button class="dropdown-toggle">&#8942;</button>
          <div class="dropdown-menu">
              <a href="#">
                  <div class="options">
                      <div class="icon"><MdAccessTime/></div>
                      <span>Watch Later</span>
                  </div>
              </a>
              <a href="#">
                  <div class="options">
                      <div class="icon"><MdShare/></div>
                      <span>Share</span>
                  </div>
              </a>
              <a href="#">
                  <div class="options">
                      <div class="icon"><MdAccessTime/></div>
                      <span>Option 3</span>
                  </div>
              </a>
            <a href="#">Option 2</a>
          </div>
        </div>
    </div>
  </div>

  <div class="video-container">
    <div class="thumbnail-container">
      <img src="">
      <div class="timestamp">06:49</div>
    </div>
    <div class="info-container">
      <div class="profile-pic">
        <img src="">
      </div>
      <div class="video-info">
        <div class="video-title">Video Title</div>
        <div class="profile-name">Profile Name</div>
      </div>

      <div class="dropdown">
        <button class="dropdown-toggle">&#8942;</button>
        <div class="dropdown-menu">
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Watch Later</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdShare/></div>
                    <span>Share</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Option 3</span>
                </div>
            </a>
          <a href="#">Option 2</a>
        </div>
      </div>
  </div>
</div>

  <div class="video-container">
    <div class="thumbnail-container">
      <img src="">
      <div class="timestamp">06:49</div>
    </div>
    <div class="info-container">
      <div class="profile-pic">
        <img src="">
      </div>
      <div class="video-info">
        <div class="video-title">Video Title</div>
        <div class="profile-name">Profile Name</div>
      </div>

      <div class="dropdown">
        <button class="dropdown-toggle">&#8942;</button>
        <div class="dropdown-menu">
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Watch Later</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdShare/></div>
                    <span>Share</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Option 3</span>
                </div>
            </a>
          <a href="#">Option 2</a>
        </div>
      </div>
  </div>
</div>

  <div class="video-container">
    <div class="thumbnail-container">
      <img src="">
      <div class="timestamp">06:49</div>
    </div>
    <div class="info-container">
      <div class="profile-pic">
        <img src="">
      </div>
      <div class="video-info">
        <div class="video-title">Video Title</div>
        <div class="profile-name">Profile Name</div>
      </div>

      <div class="dropdown">
        <button class="dropdown-toggle">&#8942;</button>
        <div class="dropdown-menu">
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Watch Later</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdShare/></div>
                    <span>Share</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Option 3</span>
                </div>
            </a>
          <a href="#">Option 2</a>
        </div>
      </div>
  </div>
</div>

  <div class="video-container">
    <div class="thumbnail-container">
      <img src="https://ih1.redbubble.net/image.2870289643.6202/st,small,507x507-pad,600x600,f8f8f8.jpg">
      <div class="timestamp">06:49</div>
    </div>
    <div class="info-container">
      <div class="profile-pic">
        <img src="data:image/jpeg;base64,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">
      </div>
      <div class="video-info">
        <div class="video-title">Joining the dark side</div>
        <div class="profile-name">BuyMyCookbook</div>
      </div>

      <div class="dropdown">
        <button class="dropdown-toggle">&#8942;</button>
        <div class="dropdown-menu">
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Watch Later</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdShare/></div>
                    <span>Share</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Option 3</span>
                </div>
            </a>
          <a href="#">Option 2</a>
        </div>
      </div>
  </div>
</div>

  <div class="video-container">
    <div class="thumbnail-container">
      <img src="">
      <div class="timestamp">06:49</div>
    </div>
    <div class="info-container">
      <div class="profile-pic">
        <img src="">
      </div>
      <div class="video-info">
        <div class="video-title">Video Title</div>
        <div class="profile-name">Profile Name</div>
      </div>

      <div class="dropdown">
        <button class="dropdown-toggle">&#8942;</button>
        <div class="dropdown-menu">
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Watch Later</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdShare/></div>
                    <span>Share</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Option 3</span>
                </div>
            </a>
          <a href="#">Option 2</a>
        </div>
      </div>
  </div>
</div>

  <div class="video-container">
    <div class="thumbnail-container">
      <img src="">
      <div class="timestamp">06:49</div>
    </div>
    <div class="info-container">
      <div class="profile-pic">
        <img src="">
      </div>
      <div class="video-info">
        <div class="video-title">Video Title</div>
        <div class="profile-name">Profile Name</div>
      </div>

      <div class="dropdown">
        <button class="dropdown-toggle">&#8942;</button>
        <div class="dropdown-menu">
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Watch Later</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdShare/></div>
                    <span>Share</span>
                </div>
            </a>
            <a href="#">
                <div class="options">
                    <div class="icon"><MdAccessTime/></div>
                    <span>Option 3</span>
                </div>
            </a>
          <a href="#">Option 2</a>
        </div>
      </div>
  </div>
</div>


</div>



<style>
	@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
.videoicons{
  display: flex-end;flex-direction: row; align-items: center;
		min-height: 100%; min-width: calc(100vw - 24rem);
		background-color: #1a1717; 
		font-family: "Roboto"; color: white;
}
.video-container {
    position: relative;
    display: inline-block;
    width: 300px;
    height: 255px;
    margin: 10px;
    border-radius: 10px;
    overflow: hidden;
    background-color: #fff;
    box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.25);
	  font-family: "Roboto";
    z-index: 1;
  }
  
  .thumbnail-container {
    position: relative;
    width: 300px;
    height: 175px;
    overflow: hidden;
    cursor: pointer;
    background-color: #cccccc;
  }
  
  .thumbnail-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  
  .timestamp {
    position: absolute;
    bottom: 10px;
    right: 10px;
    padding: 5px;
    background-color: rgba(0, 0, 0, 0.7);
    color: #fff;
    border-radius: 5px;
  }
  
  .info-container {
    display: flex;
    align-items: center;
    margin: 10px;
    flex: 1;
  }
  
  .profile-pic img {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #cccccc;
  }
  
  .video-info {
    margin-left: 10px;
  }
  
  .video-title {
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 5px;
    cursor: pointer;
    color: black;
  }
  
  .profile-name {
    font-size: 14px;
    color: #666;
  }
  
  .options {
    margin-left: auto;
    font-size: 24px;
    cursor: pointer;
  }
  
  .dropdown {
    position: relative;
    display: inline-block;
    margin-left: auto;
    font-size: 12px;
    cursor: pointer;
    z-index: 100;
  }
  
  .dropdown-toggle {
    background-color: white;
    border: none;
    font-size: 24px;
    cursor: pointer;
  }
  
  .dropdown-menu {
    display: none;
    position: absolute;
    z-index: 100;
    width: 120px;
    right: 20px;
    bottom: 20px;
    padding: 10px;
    box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.35);
  }
  
  .dropdown-menu a {
    display: block;
    padding: 10px;
    text-decoration: none;
    color: rgb(255, 255, 255);
  }

  .dropdown-menu a:hover {
    background-color: #443f3f;
    border-radius: 5px;
  }
  
  .dropdown:hover .dropdown-menu {
    display: block;
    color: white;
    background-color: #1a1717;
    border-radius: 10px;
  }

  .options {
		display: flex;
		color: white;
	}

  .options span{
      margin-left: 8px;
      font-family: "Roboto";
      font-size: 12px;
  }

	.icon {
		width: 20px; 
    height: 20px;
	}
</style>