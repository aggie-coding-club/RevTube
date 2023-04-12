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
          <img src="https://i.ytimg.com/vi/cuLprHh_BRg/maxresdefault.jpg">
          <div class="timestamp">05:52<font color="black"> Link 3 </font></div>
        </div>
        <div class="info-container">
          <div class="profile-pic">
            <img src="https://yt3.googleusercontent.com/urNLBJGryDamao5r0jmlTg84mIBOoaeJd6XR67j4nuRd0iRvv5g-MUgaowsWKCs8V_t4KwST=s176-c-k-c0x00ffffff-no-rj">
          </div>
          <div class="video-info">
            <div class="video-title">Best of Michael Jordans Playoffs</div>
            <div class="profile-name">NBA</div>
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
    <img src="https://i.ytimg.com/vi/GDSf2h9_39I/maxresdefault.jpg">
    <div class="timestamp">11:16</div>
  </div>
  <div class="info-container">
    <div class="profile-pic">
      <img src="https://yt3.ggpht.com/ytc/AGIKgqOibtncbyNaJVeUjVotNRl0r00hkiUfYEEv5XmNdw=s88-c-k-c0x00ffffff-no-rj">
    </div>
    <div class="video-info">
      <div class="video-title">Why Aliens Might Already Be On Their Way To Us</div>
      <div class="profile-name">Kurzgesagt</div>
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
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 5px;
    cursor: pointer;
    color: rgb(0, 0, 0)
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