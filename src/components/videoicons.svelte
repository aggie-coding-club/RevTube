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
      <img src="data:image/jpeg;base64,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">
      <div class="timestamp">13:32</div>
    </div>
    <div class="info-container">
      <div class="profile-pic">
        <img src="https://yt3.googleusercontent.com/ma2JJjuF8eD9-GSxYvsu3W97f0yl6cbr1EClBti4mDYUHBlT1bNwbeAgfiuZsAKA8hD2iOV7Ww=s176-c-k-c0x00ffffff-no-rj">
      </div>
      <div class="video-info">
        <div class="video-title">6 Humans vs 1 Secret AI</div>
        <div class="profile-name">Jubilee</div>
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
    font-size: 18px;
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