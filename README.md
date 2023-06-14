# music-player-html-and-css-project
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Adarsh Music Player</title>
    <!-- it is connected to two stylesheets -->
    <link rel="stylesheet" type="text/css" href="StyleSheet_main.css" />
    <!-- this is the main stylesheet -->
    <!-- desktop first approach is used for the same. -->
    <link
      rel="stylesheet"
      type="text/css"
      href="SinglePlaylistScreenStyle.css"
    />
    <!-- this is the style sheet with all the media queries -->
    <!-- this script is just for font awesome fonts -->
    <script
      src="https://kit.fontawesome.com/2d9b67a497.js"
      crossorigin="anonymous"
    ></script>
  </head>
  <!-- body -->

  <body>
    <!-- top navigation bar -->
    <nav class="navigation-bar">
      <!--This div contains the logo and title of the page-->
      <div class="title-combo">
        <div class="website-logo">
          <img src="media/website_logo.png" />
        </div>
        <div class="website-name">
          <h2>
            Adarsh
          </h2>
          <h6>
            Music Player
          </h6>
        </div>
      </div>
      <!-- this is the animated favourites text -->
      <div class="favs">
        <h4>
          Favourites
        </h4>
      </div>
      <!-- this is for search bar -->
      <div class="search-bar">
        <div>
          <!-- magnifying glass- search icon -->
          <i class="fas fa-search search-ico"></i>
        </div>
        <input type="text" name="search" placeholder="Search" />
        <div>
          <!-- mic icon -->
          <i class="fas fa-microphone mic-ico"></i>
        </div>
      </div>
      <!-- this is for notification bell -->
      <div class="notification-bell">
        <img src="media/bell_icon.png" /> Notifications
      </div>
      <!-- this is for profile picture -->
      <div class="profile-picture">
        <img src="media/profile_picture.png" />
      </div>
    </nav>
    <!-- this is the main center part of the page and it is divided into two sections, namely section 1 and section 2-->
    <!-- I have separated these sections using the aside tag for each section -->
    <main>
      <!-- aside section 1 -->
      <aside class="aside section-1">
        <!-- this is for the carousel -->
        <div class="outer-carousel">
          <div class="carousel">
            <!-- these are the 3 images in the carousel -->
            <img src="media/crousel/carousel1.jpg" />
            <img src="media/crousel/carousel2.jpg" />
            <img src="media/crousel/carousel3.jpg" />
          </div>
        </div>
        <!-- this is the latest release section -->
        <div class="latest-release">
          <h1 style="margin-bottom: 12px;">
            Latest Release
          </h1>
          <!-- this is the content of the latest release section -->
          <!-- it will contain the "cards" -->
          <div class="latest-release-content">
            <!-- first card -->
            <div class="card">
              <div>
                <!-- image corresponding to the card -->
                <img src="media/songs/willow.jpeg" />
                <!-- play button, which will be shown on hover on the card image -->
                <div class="play-button">
                  <i
                    class="fas fa-play"
                    style="width: 45%; height: 45%; display: inline-block;"
                  ></i>
                </div>
              </div>
              <!-- it will contain the name and date of release of the song -->
              <div class="song-description">
                <h3>
                  Willow
                </h3>
                <p>
                  Dec , 2020
                </p>
              </div>
              <!-- if someone clicks on the three dots, options will be shown to the user for further action -->
              <div class="options">
                <label for="latest-release-checkbox"
                  ><i class="fas fa-ellipsis-h"></i
                ></label>
                <input type="checkbox" id="latest-release-checkbox" />
                <div class="latest-release-dropdown">
                  <div class="drop-item">
                    <!-- if user clicks on play now button, he/she will be taken to the single playlist page -->
                    <p>
                      <i class="fas fa-play-circle"></i>
                      <a href="Single Playlist Screen.html">Play Now</a>
                    </p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-music"></i> Add to playlist</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                  </div>
                </div>
                <!-- duration of the song -->
                <p>
                  3:35
                </p>
              </div>
            </div>
            <!-- second card -->
            <div class="card">
              <div>
                <img src="media/songs/Weeknd.jpg" />
                <div class="play-button">
                  <i
                    class="fas fa-play"
                    style="width: 45%; height: 45%; display: inline-block;"
                  ></i>
                </div>
              </div>
              <div class="song-description">
                <h3>
                  Blinding Lights
                </h3>
                <p>
                  Dec, 2020
                </p>
              </div>
              <div class="options">
                <label for="latest-release-checkbox2"
                  ><i class="fas fa-ellipsis-h"></i
                ></label>
                <input type="checkbox" id="latest-release-checkbox2" />
                <div class="latest-release-dropdown">
                  <div class="drop-item">
                    <p>
                      <i class="fas fa-play-circle"></i>
                      <a href="Single Playlist Screen.html">Play Now</a>
                    </p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-music"></i> Add to playlist</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                  </div>
                </div>
                <p>
                  3:20
                </p>
              </div>
            </div>
            <!-- third card -->
            <div class="card">
              <div>
                <img src="media/songs/DaBaby.jpg" />
                <div class="play-button">
                  <i
                    class="fas fa-play"
                    style="width: 45%; height: 45%; display: inline-block;"
                  ></i>
                </div>
              </div>
              <div class="song-description">
                <h3>
                  ROCKSTAR
                </h3>
                <p>
                  Dec, 2020
                </p>
              </div>
              <div class="options">
                <label for="latest-release-checkbox3"
                  ><i class="fas fa-ellipsis-h"></i
                ></label>
                <input type="checkbox" id="latest-release-checkbox3" />
                <div class="latest-release-dropdown">
                  <div class="drop-item">
                    <p>
                      <i class="fas fa-play-circle"></i>
                      <a href="Single Playlist Screen.html">Play Now</a>
                    </p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-music"></i> Add to playlist</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                  </div>
                </div>
                <p>
                  3:02
                </p>
              </div>
            </div>
            <!-- fourth card -->
            <div class="card">
              <div>
                <img src="media/songs/dynamite.jpg" />
                <div class="play-button">
                  <i
                    class="fas fa-play"
                    style="width: 45%; height: 45%; display: inline-block;"
                  ></i>
                </div>
              </div>
              <div class="song-description">
                <h3>
                  Dynamite
                </h3>
                <p>
                  Dec, 2020
                </p>
              </div>
              <div class="options">
                <!-- NOTE THAT POSITION OF OPTIONS DIV IS RELATIVE -->
                <label for="latest-release-checkbox4"
                  ><i class="fas fa-ellipsis-h"></i
                ></label>
                <input type="checkbox" id="latest-release-checkbox4" />
                <div class="latest-release-dropdown">
                  <!-- POSITION OF LATEST RELEASE DROPDOWN IS ABSOLUTE TO THE RELATIVE OPTIONS. THIS IS VERY IMPORTANT AS THE DROPDOWN BOX SHOULD BE PLACED RELATIVE TO THE PARTICULAR ITEM IN THE LATEST RELEASE SECTION. IT SHOULD NOT BE ABSAOLUTE TO THE WHOLE LATEST RELEASE SECTION. THROUGH THIS PROJECT i UNDERSTOOD THE NEED OF POSITION:ABSOLUTE. ABSOLUTE POSITION AND RELATIVE ARE GENERALLY USED TOGETHER-->
                  <div class="drop-item">
                    <p>
                      <i class="fas fa-play-circle"></i>
                      <a href="Single Playlist Screen.html">Play Now</a>
                    </p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-music"></i> Add to playlist</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                  </div>
                </div>
                <p>
                  3:19
                </p>
              </div>
            </div>
            <!-- fifth card -->
            <div class="card">
              <div>
                <img src="media/songs/shit.png" />
                <div class="play-button">
                  <i
                    class="fas fa-play"
                    style="width: 45%; height: 45%; display: inline-block;"
                  ></i>
                </div>
              </div>
              <div class="song-description">
                <h3>
                  WAP
                </h3>
                <p>
                  Dec, 2020
                </p>
              </div>
              <div class="options">
                <label for="latest-release-checkbox5"
                  ><i class="fas fa-ellipsis-h"></i
                ></label>
                <input type="checkbox" id="latest-release-checkbox5" />
                <div class="latest-release-dropdown">
                  <div class="drop-item">
                    <p>
                      <i class="fas fa-play-circle"></i>
                      <a href="Single Playlist Screen.html">Play Now</a>
                    </p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-music"></i> Add to playlist</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                  </div>
                </div>
                <p>
                  4:44
                </p>
              </div>
            </div>
            <!-- sixth card -->
            <div class="card">
              <div>
                <img src="media/songs/falling.jpg" />
                <div class="play-button">
                  <i
                    class="fas fa-play"
                    style="width: 45%; height: 45%; display: inline-block;"
                  ></i>
                </div>
              </div>
              <div class="song-description">
                <h3>
                  Falling
                </h3>
                <p>
                  Dec, 2020
                </p>
              </div>
              <div class="options">
                <label for="latest-release-checkbox6"
                  ><i class="fas fa-ellipsis-h"></i
                ></label>
                <input type="checkbox" id="latest-release-checkbox6" />
                <div class="latest-release-dropdown">
                  <div class="drop-item">
                    <p>
                      <i class="fas fa-play-circle"></i>
                      <a href="Single Playlist Screen.html">Play Now</a>
                    </p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-music"></i> Add to playlist</p>
                  </div>
                  <hr />
                  <div class="drop-item">
                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                  </div>
                </div>
                <p>
                  2:39
                </p>
              </div>
            </div>
          </div>
        </div>
        <!-- this is the popular artists section -->
        <div class="popular-artists">
          <!-- this is the heading of popular artists section -->
          <h1 style="margin-bottom: 12px;">
            Popular Artists
          </h1>
          <!-- this contains the content of the popular artists section -->
          <div class="popular-artist-content">
            <!-- if user clicks on any one artist, it will redirect the user to the second page -->
            <!-- following is the list of artists -->
            <!-- first artist -->
            <a href="Single Playlist Screen.html">
              <div>
                <img src="media/popular artists/adele.jpg" />
                <div><i class="fas fa-play"></i></div>
                <p>
                  Adele
                </p>
              </div>
            </a>
            <!-- second artist -->
            <a href="Single Playlist Screen.html">
              <div>
                <img src="media/popular artists/billie eilish.jpg" />
                <div><i class="fas fa-play"></i></div>
                <p>
                  Billie Eilish
                </p>
              </div>
            </a>
            <!-- third artist -->
            <a href="Single Playlist Screen.html">
              <div>
                <img
                  src="media/popular artists/bruno mars.jpg"
                  width="15vw"
                  height="10vw"
                />
                <div><i class="fas fa-play"></i></div>
                <p>
                  Bruno Mars
                </p>
              </div>
            </a>
            <!-- fourth artist -->
            <a href="Single Playlist Screen.html">
              <div>
                <img src="media/popular artists/Camila Cabello.jpg" />
                <div><i class="fas fa-play"></i></div>
                <p>
                  Camila Cabello
                </p>
              </div>
            </a>
            <!-- fifth artist -->
            <a href="Single Playlist Screen.html">
              <div>
                <img src="media/popular artists/drake.jpg" />
                <div><i class="fas fa-play"></i></div>
                <p>
                  Drake
                </p>
              </div>
            </a>
            <!-- 6th artist -->
            <a href="Single Playlist Screen.html">
              <div>
                <img src="media/popular artists/ed sheeran.jpg" />
                <div><i class="fas fa-play"></i></div>
                <p>
                  Ed Sheeran
                </p>
              </div> </a
            ><!-- 7th artist -->
            <a href="Single Playlist Screen.html">
              <div>
                <img src="media/popular artists/eminem.jpg" />
                <div><i class="fas fa-play"></i></div>
                <p>
                  Eminem
                </p>
              </div> </a
            ><!-- 8th artist -->
            <a href="Single Playlist Screen.html">
              <div>
                <img src="media/popular artists/Katy perry.jpg" />
                <div><i class="fas fa-play"></i></div>
                <p>
                  Katy Perry
                </p>
              </div>
            </a>
            <!-- 9th artist -->
            <a href="Single Playlist Screen.html">
              <div>
                <img src="media/popular artists/sixnine.jpg" />
                <div><i class="fas fa-play"></i></div>
                <p>
                  6ix9ine
                </p>
              </div>
            </a>
            <!-- 10th artist -->
            <a href="Single Playlist Screen.html">
              <div>
                <img src="media/popular artists/posty.png" />
                <div><i class="fas fa-play"></i></div>
                <p>
                  Post Malone
                </p>
              </div>
            </a>
          </div>
        </div>
        <!-- this is the music themes part, the one with the tri-gradient background -->
        <div class="music-themes">
          <!-- this div will be the logo of music themes, see the output, the one with 3 squares/rects  -->
          <!-- the logo with orange, green and yellow color -->
          <div class="stations">
            <div id="div1">
              <div id="div2">
                <div id="div3">
                  <img src="media/website_logo.png" />
                  <p>Stations</p>
                </div>
              </div>
            </div>
          </div>
          <!-- this is the content part of them themes -->
          <!-- the one which changes colors on hover -->
          <div class="theme-main">
            <div class="theme-content">
              <img src="media/music themes/chill.jpg" />
              <p>Vibe</p>
            </div>
            <div class="theme-content">
              <img src="media/music themes/rock.jpg" />
              <p>Rock</p>
            </div>
            <div class="theme-content">
              <img src="media/music themes/love.jpg" />
              <p>Love</p>
            </div>
            <div class="theme-content">
              <img src="media/music themes/pop.jpg" />
              <p>Pop</p>
            </div>
            <div class="theme-content">
              <img src="media/music themes/retro.jpg" />
              <p>Retro</p>
            </div>
            <div class="theme-content">
              <img src="media/music themes/workout.jpg" />
              <p>GYM</p>
            </div>
          </div>
        </div>
        <!-- this is another themes portion, that electronic, party and road theme -->
        <div class="music-themes-2">
          <!-- 3 divs content -->
          <div class="outer-div">
            <div class="inner-div">
              <span>party</span>
            </div>
          </div>
          <div class="outer-div">
            <div class="inner-div">
              <span>Electronic</span>
            </div>
          </div>
          <div class="outer-div">
            <div class="inner-div">
              <span>Travel</span>
            </div>
          </div>
        </div>
        <!-- div over -->
        <!-- this div contains the language section of the page -->
        <!-- "language class is common to both hindi and english sections" -->
        <!-- in this way redundancy is handled. considering the re-usability of the code -->
        <div class="language english">
          <!-- latest english section -->
          <h1 class="language-heading">
            Latest English
          </h1>
          <!-- contents of latest english -->
          <div class="language-content">
            <div>
              <img src="media/latest english/I'll Wait.jpg" />
              <p>I'll Wait</p>
              <p>Aug 11, 2017</p>
            </div>
            <div>
              <img src="media/latest english/let me go.jpg" />
              <p>Let me Go!</p>
              <p>Aug 11, 2017</p>
            </div>
            <div>
              <img src="media/latest english/qurantine clean.jpg" />
              <p>Qurantine Clean</p>
              <p>Aug 11, 2017</p>
            </div>
            <div>
              <img src="media/latest english/roar.jpg" />
              <p>Roar</p>
              <p>Aug 11, 2017</p>
            </div>
            <div>
              <img src="media/latest english/toosie slide.jpg" />
              <p>Toosie Slide</p>
              <p>Aug 11, 2017</p>
            </div>
            <div>
              <img src="media/latest english/uptown funk.png" />
              <p>Uptown Funk</p>
              <p>Aug 11, 2017</p>
            </div>
          </div>
        </div>
        <!-- this is the hindi section -->
        <div class="language hindi">
          <!-- hindi section heading -->
          <h1 class="language-heading">
            Latest Hindi
          </h1>
          <!-- hindi section contents -->
          <div class="language-content">
            <div>
              <img src="media/latest hindi/baarish.jpeg" />
              <p>Baarish</p>
              <p>Aug 11, 2017</p>
            </div>
            <div>
              <img src="media/latest hindi/galiyaan.jpg" />
              <p>Galiyaan</p>
              <p>Aug 11, 2017</p>
            </div>
            <div>
              <img src="media/latest hindi/giveme some sunshine.jpg" />
              <p>Give me Some Sunshine</p>
              <p>Aug 11, 2017</p>
            </div>
            <div>
              <img src="media/latest hindi/kaun tujhe.jpg" />
              <p>Kaun Tujhe</p>
              <p>Aug 11, 2017</p>
            </div>
            <div>
              <img src="media/latest hindi/tera ban jaunga.jpg" />
              <p>Tera Ban Jaunga</p>
              <p>Aug 11, 2017</p>
            </div>
            <div>
              <img src="media/latest hindi/tere sang yara.jpg" />
              <p>Tere Sang Yaara</p>
              <p>Aug 11, 2017</p>
            </div>
          </div>
        </div>
      </aside>
      <!-- one aside section is complete -->
      <!-- now the second aside section will start from here -->
      <!-- the page is responsive. please try reducing the width of the page -->
      <!-- the aside section will collapse and a "more button will be shown to you." -->
      <!-- clicking on this more button, you will be shown the aside section 2  -->
      <!-- its position will be absolute at lower resolutions -->
      <!-- this is the label for that more button -->
      <label for="more"><i class="fas fa-angle-double-left"></i>More</label>
      <!-- this is that more button -->
      <!-- and this is the check box. this will always be hidden -->
      <!-- check the stylesheet_main.css when the label is clicked, this checkbox will be checked -->
      <!-- which will invoke the aside section 2 on lower resolutions -->
      <input type="checkbox" id="more" />
      <!-- here starts the section 2 of our page -->
      <aside class="aside section-2">
        <!-- this is the section heading part. the heading will be static -->
        <div class="heading">
          <h1>Playlist</h1>
          <h4>
            <a href="#queue-option-box"
              >Queue <i class="fas fa-chevron-circle-down"></i
            ></a>
          </h4>
        </div>
        <!-- this is the queue box which will be shown when the user clicks on the Queue button -->
        <!-- it will have 3 options, playlists, favourite songs and Close button. it will close when one clicks on the close button. -->
        <div class="queue-options" id="queue-option-box">
          <p>
            <a href style="color: #007bff; font-weight: bolder;">Playlists</a>
          </p>
          <hr />
          <p>
            <a href style="color: #007bff; font-weight: bolder;"
              >Favourite songs</a
            >
          </p>
          <hr />
          <p><a href="#" style="color: red; font-weight: bolder;">Close</a></p>
        </div>
        <!-- this is the content of the playlist. it will be dynamic. -->
        <div class="playlist-content">
          <!-- first playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <!-- index -->
              <div style="margin-right: 4px;">
                01
              </div>
              <div class="coverer">
                <!-- coverer class is for those items which when hovered will show an effect -->
                <!-- in this effect, when the user hovers on the item, it will show black background -->
                <!-- with opacity value less than 1 and a play button icon at the center -->
                <img
                  src="media/playlist/austin-neill-kKlVSrFbjYY-unsplash.jpg"
                />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <!-- name and author of the song -->
              <div>
                <div>
                  Alone
                </div>
                <p>
                  Alan Walker
                </p>
              </div>
            </div>
            <!-- like button -->
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- second playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                02
              </div>
              <div class="coverer">
                <img src="media/playlist/after.jpg" />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  Alone Again
                </div>
                <p>
                  Weeknd
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- third playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                03
              </div>
              <div class="coverer">
                <img src="media/playlist/stoney.jpg" />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  White Iverson
                </div>
                <p>
                  Post Malone
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- fourth playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                04
              </div>
              <div class="coverer">
                <img src="media/playlist/stoney.jpg" />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  Go Flex
                </div>
                <p>
                  Post Malone
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- fifth playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                05
              </div>
              <div class="coverer">
                <img src="media/playlist/stoney.jpg" />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  Better Now
                </div>
                <p>
                  Post Malone
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- sixth playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                06
              </div>
              <div class="coverer">
                <img src="media/playlist/after.jpg" />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  Hardest To Love
                </div>
                <p>
                  Weeknd
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- seventh playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                07
              </div>
              <div class="coverer">
                <img src="media/playlist/beer.jpg" />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  Pysco
                </div>
                <p>
                  Post Malone
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- eighth playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                08
              </div>
              <div class="coverer">
                <img src="media/playlist/beer.jpg" />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  Rockstar
                </div>
                <p>
                  Post Malone & 21 Savage
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- ninth playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                09
              </div>
              <div class="coverer">
                <img src="media/playlist/stoney.jpg" />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  Deja Vu
                </div>
                <p>
                  Post Malone & Justin Beiber
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- tenth playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                10
              </div>
              <div class="coverer">
                <img src="media/popular artists/billie eilish.jpg" />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  Bad Guy
                </div>
                <p>
                  Billie Eilish
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- eleventh playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                11
              </div>
              <div class="coverer">
                <img src="media/songs/sorry.jpg" />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  Sorry
                </div>
                <p>
                  Justin Bieber
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
          <!-- twelfth playlist item -->
          <div class="playlist-item">
            <div class="left-content">
              <div style="margin-right: 4px;">
                12
              </div>
              <div class="coverer">
                <img
                  src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/166e992b-4534-4bd8-bb41-3be395f82cde/daojfrr-facc1540-40b8-455f-b8b6-ba4f14738b32.png/v1/fill/w_894,h_894,q_75,strp/bts___wings_by_goldendesigncover-daojfrr.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwic3ViIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl0sIm9iaiI6W1t7InBhdGgiOiIvZi8xNjZlOTkyYi00NTM0LTRiZDgtYmI0MS0zYmUzOTVmODJjZGUvZGFvamZyci1mYWNjMTU0MC00MGI4LTQ1NWYtYjhiNi1iYTRmMTQ3MzhiMzIucG5nIiwid2lkdGgiOiI8PTg5NCIsImhlaWdodCI6Ijw9ODk0In1dXX0.VXwplpd8rbngUYyW306GbKo_PdH8B_g3gw3fr1V0Mes"
                />
                <div class="play-button">
                  <i class="fas fa-play" aria-hidden="true"></i>
                </div>
              </div>
              <div>
                <div>
                  Golden
                </div>
                <p>
                  BTS
                </p>
              </div>
            </div>
            <div class="right-content">
              <i class="far fa-heart"></i>
            </div>
          </div>
        </div>
      </aside>
    </main>
    <!-- main part of the page is over. -->
    <!-- this is the footer part. -->
    <!-- its position will be fixed to the screen bottom. -->
    <footer>
      <div class="active-song-description">
        <!-- song image -->
        <div id="song-image">
          <img src="media/latest english/roar.jpg" />
        </div>
        <!-- song name and author -->
        <div class="song-desc">
          <div>
            Imagine by John
          </div>
          <div>
            John Lenon
          </div>
          <!-- heart icon and ban icon -->
        </div>
        <div class="heart-and-ban-icon">
          <span>
            <i class="far fa-heart"></i>
          </span>
          <span>
            <i class="fas fa-ban"></i>
          </span>
        </div>
      </div>
      <!-- these are the main player controls -->
      <div class="player">
        <div class="controls">
          <div><i class="fas fa-random"></i></div>
          <div><i class="fas fa-step-backward"></i></div>
          <div><i class="fas fa-pause-circle"></i></div>
          <div><i class="fas fa-step-forward"></i></div>
          <div><i class="fas fa-redo"></i></div>
        </div>
        <!-- this is the slider -->
        <div id="slider">
          <!-- current time -->
          <div class="time">
            1:39
          </div>
          <div class="slidecontainer">
            <input
              type="range"
              min="0"
              max="100"
              value="0"
              class="slider"
              id="myRange"
            />
          </div>
          <!-- total time -->
          <div class="time">
            4:44
          </div>
        </div>
      </div>
      <!-- other icons including the volume slider and all -->
      <div class="extras">
        <div>
          <i class="fas fa-list-ul"></i>
        </div>
        <div>
          <i class="fas fa-laptop"></i>
        </div>
        <div>
          <i class="fas fa-volume-up"></i>
        </div>
        <div class="slidecontainer" style="width: 30%;">
          <input
            type="range"
            min="0"
            max="100"
            value="0"
            class="slider"
            id="myRange"
            style="margin-top: 0px;"
          />
        </div>
        <div>
          <i class="fas fa-expand-alt"></i>
        </div>
      </div>
    </footer>
  </body>
</html>
 
 
 
 
 #csss code
 single playlist screenstyle.css
 :root {
  --background-image: url("media/background_image/3541800.jpg");
  --jumbotron-color: #141b41;
  --playlist-items-background-color: #1a1e33;
  --playlist-items-background-color-on-hover: #2e3249;
}
body {
  /* background-image: var(--background-image); */
  background-image: var(--background-image);

  /* 	background-position: center;
	background-size: cover;
	background-repeat: no-repeat; */
  margin: 0px;
  font-family: "Segoe UI", Arial, sans-serif;
  color: white;
}
/* removing all the styles from the links and formatting them white */
a {
  text-decoration: none;
  color: white;
}
/* removing margin for all the textual elements */
h1,
h2,
h3,
h4,
h5,
h6,
p {
  margin: 0px;
}
/* top navigation bar */
.navigation-bar {
  height: auto;
  width: auto;
  background-image: linear-gradient(180deg, black, rgba(0, 0, 0, 0));
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  box-sizing: border-box;
  padding-left: 5%;
  padding-right: 5%;
  transition: all ease-in-out 1s; /* when the navbar loads, every property transits for 1s */
}
/* all the divs inside the navigation bar should be placed side by side*/
.navigation-bar > div {
  display: inline-block;
}
/* animation for the website logo */
@keyframes rotating {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
/* website logo image */
.website-logo img {
  height: 50px;
  width: 50px;
  border-radius: 100%;
  animation-name: rotating;
  animation-timing-function: ease-in-out;
  animation-duration: 2s;
  animation-iteration-count: infinite;
}
/* website title and general description */
.title-combo > div {
  vertical-align: middle;
  display: inline-block;
}
/* animation for favoutites text */
@keyframes flexible {
  75% {
    transform: scale(1.1);
  }
  100% {
    transform: scaleX(1);
  }
}
/* favourites text */
.favs {
  animation-name: flexible;
  animation-timing-function: ease-in-out;
  animation-duration: 2s;
  perspective: 10000px;
  transform-style: preserve-3d;
  animation-iteration-count: infinite;
}

/* search bar */
.search-bar {
  width: 20%;
  position: relative;
}
/* changing the default style of the input bar */
.search-bar input {
  width: 100%;
  font-size: 16px;
  text-decoration: none;
  border-radius: 18px;
  border: none;
  padding: 5px;
  font-weight: 500;
  text-align: center;
  transition: all ease-in-out 0.1s;
}
/* search icon for input bar */
.search-ico {
  color: rgba(0, 0, 0, 0.5);
}
/* mic icon for input */
.mic-ico {
  color: rgba(0, 0, 0, 0.5);
}
/* search icon */
.search-bar > div:nth-child(1) {
  display: inline-block;
  position: absolute;
  width: min-content;
  left: 5%;
  top: 10%;
  transition: all ease-in-out 0.1s;
}
/* mic icon */
.search-bar > div:nth-child(3) {
  display: inline-block;
  position: absolute;
  width: min-content;
  right: 0%;
  top: 10%;
  transition: all ease-in-out 0.1s;
}
/* when the user clicks on the search bar, there should be no blue outlining */
input:focus {
  outline: none;
}
/* animation for bell image */
@keyframes ringing_bell {
  0% {
    transform: rotate(-15deg);
  }
  50% {
    transform: rotate(15deg);
  }
  100% {
    transform: rotate(-15deg);
  }
}
/* notification bell image */
.notification-bell img {
  width: 40px;
  height: 30px;
  animation-name: ringing_bell;
  animation-duration: 0.3s;
  animation-timing-function: ease-in-out;
  animation-iteration-count: infinite;
}
/* profile picture of the user */
.profile-picture img {
  width: 45px;
  height: 45px;
  border-radius: 100%;
}
/* navigation bar is completed here */
/* //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// */
/* main */
main {
  width: 100%;
  padding: 0% 3%;
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  transition: all ease-in-out 1s;
}
/* there are two aside sections both of them will have this class 
(I have taken care of the re-usability of the classes and removed redundancy) */
.aside {
  display: inline-block;
  overflow: hidden;
}
/* section one of the main part */
.section-1 {
  width: 70%;
  height: 85vh;
  overflow: scroll;
}
/* overflow should be scrollable but the scroll bar should be hidden*/
.section-1::-webkit-scrollbar {
  display: none;
}
/* section 2 of the main part */
.section-2 {
  width: 28%;
  height: 85vh;
  z-index: 2;
}

/* aside section 1 */
/* jumbotron */
.jumbotron {
  height: 20vw;
  width: 100%;
  margin-top: 12px;
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  background-color: var(--jumbotron-color);
  margin-bottom: 40px;
  position: relative;
}
/* image insider jumbotron */
.jumbotron-image {
  height: 20vw;
  width: 20vw;
  background-image: linear-gradient(to bottom, transparent, rgba(20, 27, 65, 1)),
    url("media/latest\ english/roar.jpg");
  background-size: cover;
}
/* right part of the jumbotron */
.jumbotron-detail {
  width: 67%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  box-sizing: border-box;
  padding-right: 12px;
}
/* descriptive part contains the descripton of the song and action part contains the follow and play buttons */
.descriptive-part,
.action-part {
  width: 100%;
  height: max-content;
}
/* song name and followers */
.song-name-main,
.followers {
  display: inline-block;
}
/* song name heading properties */
.song-name-main h1 {
  font-size: 2vw;
}
/* follower count */
.followers {
  position: absolute;
  right: 0%;
  top: 5%;
}
/* self explanatory */
.followers,
.author {
  font-size: 1.5vw;
}
/* description of the jumbotron */
.desc {
  font-size: 1vw;
}
/* action part */
/* .action-part {
	padding-top: 2vw;
} */
.action-part p {
  font-size: 1vw;
}
.btns > button {
  border: 0px;
  height: 3vw;
  width: 10vw;
  color: white;
  font-size: 1.2vw;
}
/* play button */
.btns > button:nth-child(1) {
  background-image: linear-gradient(-19deg, red 0%, blue 100%);
}
/* follow button */
.btns > button:nth-child(2) {
  background-color: transparent;
}
/* particular item in the playlist */
.playlist-item {
  /* height:60px;
    width:100%; */
  height: 8vh;

  box-sizing: border-box;
  background-color: var(--playlist-items-background-color);
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 12px;
  /* transition: all ease-in-out 0.1s; */
}
/* playlist item hovering effects */
.playlist-item:hover {
  background-color: var(--playlist-items-background-color-on-hover);
}
/* left part if the playlist item */
.left {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  width: 30%;
  height: 100%;
  padding: 0% 1%;
}
/* center part of the playlist item which contains the duration length of the song */
.center {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  width: min-content;
  height: 100%;
}
/* right part of the playlist item, which contains icons */
.right {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  width: 50px;
  height: 100%;
  padding-right: 2%;
} /* now adjusting the contents of left, center and right parts */
.left > div:nth-child(2) {
  height: 80%;
  min-width: 50px;
  max-width: 50px;
  margin: 0px 12% 0px 12%;
  position: relative;
}
.left > div:nth-child(2) img {
  width: 100%;
  height: 100%;
}
.left > div:nth-child(3) p {
  color: rgb(185, 185, 185);
}
/* customizing the play button */
.play-btn {
  background-color: black;
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0%;
  left: 0%;
  opacity: 0;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  transition: all ease-in-out 0.1s;
}
/* on hover effects */
.play-btn:hover {
  opacity: 0.7;
}
/* adjusting fonts in the playlist items  */
.left div p {
  font-size: 14px;
}
.center {
  font-size: 12px;
  color: rgb(185, 185, 185);
}
.right {
  color: rgb(185, 185, 185);
}
.right div:nth-child(2) {
  margin-left: 27%;
}
/* second section of the page starts here */
/* ///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// */
/* "more" button properties */
label {
  display: none;
  position: absolute;
  right: 0%;
  top: 20%;
  padding-bottom: 5px;
  z-index: 3;
  box-shadow: 0px 0px 2px 1px white;
  width: 70px;
  font-size: 20px;
  height: 21px;
  text-align: center;
  background-image: linear-gradient(red, blue);
}
/* on a normal display, it will be hidden */
label ~ input {
  display: none;
}
/* ASIDE SECTION -2 */
/* this is the first section heading of the aside section 2 */
.section-heading {
  margin-top: 10px;
  position: relative;
  margin-bottom: 12px;
}
/* adjusting for side by side display */
.section-heading div,
.section-heading h1 {
  display: inline-block;
}
.section-heading h1 {
  font-size: 23px;
}
.section-heading div {
  position: absolute;
  bottom: 0%;
  right: 0px;
  font-size: 14px;
}

.list {
  height: 36vh;
  overflow: scroll;
}
/* hiding the scrollbar */
.list::-webkit-scrollbar {
  display: none;
}
/* this is particular item in the "list  container*/
.list-item {
  width: 100%;
  height: 100px;
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  position: relative;
  margin-bottom: 12px;
}
/* hovering effect for the list item */
.list-item:hover {
  background-color: var(--playlist-items-background-color-on-hover);
}
/* adjusting the name and image of the songs relative to their original position */
.list-item > div:nth-child(1) {
  width: 100px;
  height: 100%;
  position: relative;
}
.list-item > div:nth-child(1) > img {
  width: 100%;
  height: 100%;
}
.author-name {
  font-size: 12px;
  color: rgb(185, 185, 185);
}
.extra {
  text-align: right;
  height: 100%;
}
/* ////////////////////////////////////////////////////////////////////////////////////////////////////////////// */

/* Footer section starts here*/
/* this is the container for the whole footer */
footer {
  position: absolute;
  bottom: 1px;
  width: 100%;
  height: 60px;
  background-color: #282828;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-content: center;
  flex-wrap: nowrap;
  padding: 0px 3%;
  box-sizing: border-box;
  z-index: 6;
}
/* footer is divided into 3 parts */
/* 1. first part of the footer */
.active-song-description {
  /* border:1px solid white; */
  height: 90%;
  width: 25%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
}
/* the current song which is being played, this is the image container for that. */
#song-image {
  width: 50px;
  height: 50px;
  min-width: 50px;
  min-height: 50px;
}
/* current song image */
#song-image img {
  width: 100%;
  height: 100%;
}
/* heart and ban icon */
.heart-and-ban-icon {
  height: 100%;
  padding-top: 4%;
}
/* song decscription */
.song-desc {
  margin-right: 1%;
  margin-left: 1%;
}
/* song name */
.song-desc div:nth-child(1) {
  font-size: 14px;
}
/* song author */
.song-desc div:nth-child(2) {
  font-size: 12px;
}

/* 2. Second part of the footer*/
.player {
  width: 45%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  flex-wrap: nowrap;
}
/* controls is the container for all the center controls of the player */
.controls {
  width: 40%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  font-size: 20px;
}
/* this is the song-duration slider */
#slider {
  width: 100%;
  font-size: 12px;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  align-items: center;
  justify-content: center;
  margin-top: 5px;
}
/* ////////// */
.time {
  margin: 0px 10px;
}

/* adjusting the slider for better visuals */
.slidecontainer {
  width: 100%;
}

/* for audio and main center player */
.slider {
  -webkit-appearance: none;
  width: 100%;
  height: 5px;
  background: #d3d3d3;
  outline: none;
  opacity: 0.5;
  -webkit-transition: 0.2s;
  transition: opacity 0.2s;
}

/* hover effect for the slider */
.slider:hover {
  opacity: 1;
}

/* these are for adjusting the dimensions and default styling of the long-slider */
.slider::-webkit-slider-thumb {
  -webkit-appearance: none;
  appearance: none;
  width: 17px;
  height: 17px;
  border-radius: 50%;
  background: #007bff;
  cursor: pointer;
}

/* this is the circular thumb, which can be moved across the div */
.slider::-moz-range-thumb {
  width: 25px;
  height: 25px;
  background: #4caf50;
  cursor: pointer;
}

/* third part of the footer */
/* this contains the extra icons and slider for volume */
/* this is also a container */
.extras {
  width: 20%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
}

/* these are all the media queries for "single playlist screen.html" page with the desktop first approach*/
@media screen and (max-width: 1200px) {
  /* animated favourites text will be hidden for this viewport width*/
  .favs {
    display: none !important;
  }
  /* reduced size of search bar */
  .search-bar {
    width: 30%;
  }
  input {
    font-size: 11px !important;
  }
  .song-name-main h1 {
    font-size: 2.4vw;
  }
  .desc {
    font-size: 1.2vw;
  }
}
@media screen and (max-width: 900px) {
  /* jumbotron description */
  .desc {
    font-size: 1.6vw;
  }
  /* more button vil ve visible and section 2 will be hidden by default for this viewport */
  label {
    display: block;
  }
  /* hidden section 2 by default */
  .section-2 {
    visibility: hidden;
    opacity: 0;
    position: absolute;
    width: 300px;
    height: 68vh;
    background-color: #050043;
    box-shadow: 0px 0px 2px 1px white;
    right: 0px;
    top: 23.5%;
    overflow: scroll;
    padding-left: 10px;
    z-index: 5;
    padding-right: 5px;
    transition: visibility ease-in-out 0.3s;
    transition: opacity ease-in-out 0.3s;
  }
  /* more button */
  input[type="checkbox"]:checked ~ .section-2 {
    visibility: visible;
    opacity: 1;
  }
  .list {
    overflow: hidden;
    height: auto;
  }
  .list-item {
    background-color: #1a1e33;
  }
  /* hide section 2 scrollbar */
  .section-2::-webkit-scrollbar {
    display: none;
  }
  /* when the section 2 is hidden, section-1 width becomes 100% to cover the whole page */
  .section-1 {
    width: 100%;
  }
  /* jumbotron */
  .jumbotron {
    height: 30vw;
  }
  /* image in the jumbotron */
  .jumbotron-image {
    height: 30vw;
    width: 30vw;
  }
  /* buttons and all */
  .action-part p {
    font-size: 2vw;
  }
  .btns > button {
    height: 4vw;
    width: 11vw;
    font-size: 1.7vw;
  }
}
@media screen and (max-width: 700px) {
  /* in the screens of this width, generally volume buttons are provided at the side. */
  /* so there is no need for the volume slider at this width. so i have removed them from the display */
  /* followers and author */
  .followers,
  .author {
    font-size: 2vw;
  }
  /* jumbotron description */
  .desc {
    font-size: 1.8vw;
  }
  /* extra icons in the footer at the right hand side */
  .extras > div:nth-child(3) {
    display: none;
  }
  .extras > div:nth-child(4) {
    display: none;
  }
}
@media screen and (max-width: 550px) {
  /* this is the most important media query */
  /* navigation bar section */
  /* website image */
  .website-logo img {
    height: 30px;
    width: 30px;
  }
  /* website name */
  .website-name h1 {
    font-size: 3vw;
  }
  /* website name */
  .website-name h4 {
    font-size: 2vw;
  }
  /* notification bell */
  .notification-bell img {
    width: 20px;
    height: 20px;
  }
  /* profile picture */
  .profile-picture img {
    width: 30px;
    height: 30px;
  }
  /* notification bell and profile picture */
  .notification-bell,
  .profile-picture {
    margin-top: 8px;
  }
  .song-name-main h1 {
    font-size: 3vw;
  }
  /* followers and author */
  .followers,
  .author {
    font-size: 3vw;
  }
  /* jumbotron description */
  .desc {
    font-size: 3vw;
    padding-left: 4px;
  }
  /* buttons and all in the jumbotron */
  .action-part {
    padding-top: 0px;
  }
  /* jumbotron */
  .jumbotron {
    height: 60vw;
    text-align: justify;
  }
  /* image in the jumbotron */
  .jumbotron-image {
    height: 60vw;
    width: 60vw;
  }
  /* buttons and stuff */
  .btns > button {
    height: 8vw;
    width: 17vw;
    font-size: 3.2vw;
  }
  /* this is the image in the footer section of the page. due to less space, it has to be removed at such lower resolutions. */
  /* there is another option, but it will look messy and small */
  #song-image {
    display: none;
  }
}


style sheet.css





:root {
  /* trying various background colors and images and gradients */
  /* --background-image: linear-gradient(-90deg, #2E3192 , #1BFFFF); */
  /* --background-image: linear-gradient(-90deg, #D4145A , #FBB03B); */
  /* --background-image: linear-gradient(-90deg, #662D8C , #ED1E79); */ /* best one till now */
  /* --background-image: linear-gradient(-90deg, #FF512F , #DD2476); */
  /* --background-image: linear-gradient(-90deg, #C33764 , #1D2671); */ /* suitable for the text */
  /* --background-image: linear-gradient(90deg, #764BA2 , #667EEA); */
  /* trying other combinations */
  /* --background-image: linear-gradient(90deg, #8E0E00 , #1F1C18); */ /* it was also looking decent */
  /* --background-image: linear-gradient(90deg, #fc00ff , #00dbde); */

  /* now trying combination of 3 colors */
  /* --background-image: linear-gradient(90deg,#833ab4, #fd1d1d, #fcb045); */
  /* --background-image: linear-gradient(90deg,#21D4FD, #B721FF); */
  /* --background-image:url("background_image/2725544.jpg"); */
  /* triend all the above gradients, finally liked the gradient vectored image */
  --background-image: url(media/background_image/2725544.jpg);
  --music-themes-background-image: linear-gradient(
    90deg,
    #833ab4,
    #fd1d1d,
    #fcb045
  );
}
body {
  background-image: var(--background-image);
  margin: 0px;
  font-family: "Segoe UI", Arial, sans-serif;
  color: white;
}
/* removing margin for all the textual elements */
h1,
h2,
h3,
h4,
h5,
h6,
p {
  margin: 0px;
}
/* removing all the styles from the links and formatting them white */
a {
  text-decoration: none;
  color: white;
}
/* top navigation bar */
.navigation-bar {
  height: auto;
  width: auto;
  background-image: linear-gradient(180deg, black, rgba(0, 0, 0, 0));
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  box-sizing: border-box;
  padding-left: 5%;
  padding-right: 5%;
  transition: all ease-in-out 1s; /* when the navbar loads, every property transits for 1s */
}
/* all the divs inside the navigation bar should be placed side by side*/
.navigation-bar > div {
  display: inline-block;
}
/* animation for the website logo */
@keyframes rotating {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
/* website logo image */
.website-logo img {
  height: 50px;
  width: 50px;
  border-radius: 100%;
  animation-name: rotating;
  animation-timing-function: ease-in-out;
  animation-duration: 2s;
  animation-iteration-count: infinite;
}
/* website function */
.website-name h4 {
  color: rgb(80, 220, 255);
}
/* website title and general description */
.title-combo > div {
  vertical-align: middle;
  display: inline-block;
}
/* animation for favoutites text */
@keyframes flexible {
  75% {
    transform: scale(1.1);
  }
  100% {
    transform: scaleX(1);
  }
}
/* favourites text */
.favs {
  animation-name: flexible;
  animation-timing-function: ease-in-out;
  animation-duration: 2s;
  perspective: 10000px;
  transform-style: preserve-3d;
  animation-iteration-count: infinite;
}
/* search bar */
.search-bar {
  width: 20%;
  position: relative;
}
/* changing the default style of the input bar */
.search-bar input {
  width: 100%;
  font-size: 16px;
  text-decoration: none;
  border-radius: 18px;
  border: none;
  padding: 5px;
  font-weight: 500;
  text-align: center;
  transition: all ease-in-out 0.1s;
}
/* search icon for input bar */
.search-ico {
  color: rgba(0, 0, 0, 0.5);
}
/* mic icon for input */
.mic-ico {
  color: rgba(0, 0, 0, 0.5);
}
/* search icon */
.search-bar > div:nth-child(1) {
  display: inline-block;
  position: absolute;
  width: min-content;
  left: 5%;
  top: 10%;
  transition: all ease-in-out 0.1s;
}
/* mic icon */
.search-bar > div:nth-child(3) {
  display: inline-block;
  position: absolute;
  width: min-content;
  right: 0%;
  top: 10%;
  transition: all ease-in-out 0.1s;
}
/* when the user clicks on the search bar, there should be no blue outlining */
input:focus {
  outline: none;
}
/* animation for bell image */
@keyframes ringing_bell {
  0% {
    transform: rotate(-15deg);
  }
  50% {
    transform: rotate(15deg);
  }
  100% {
    transform: rotate(-15deg);
  }
}
/* notification bell image */
.notification-bell img {
  width: 40px;
  height: 30px;
  animation-name: ringing_bell;
  animation-duration: 0.4s;
  animation-timing-function: ease-in-out;
  animation-iteration-count: infinite;
  animation-delay: 10s;
  position: first;
}
/* profile picture of the user */
.profile-picture img {
  width: 45px;
  height: 45px;
  border-radius: 100%;
}
/* navigation bar is completed here */
/* //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// */
/* main */
main {
  width: 100%;
  padding: 0% 3%;
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  transition: all ease-in-out 1s;
}
/* there are two aside sections both of them will have this class 
(I have taken care of the re-usability of the classes and removed redundancy) */
.aside {
  display: inline-block;
  overflow: hidden;
}
/* section one of the main part */
.section-1 {
  width: 70%;
  height: 86vh;
  overflow: scroll;
  overflow-x: hidden;
}
/* overflow should be scrollable but the scroll bar should be hidden*/
.section-1::-webkit-scrollbar {
  display: none;
}
/* section 2 of the main part */
.section-2 {
  width: 28%;
  height: 86vh;
}
/* aside section 1 */
.outer-carousel {
  position: relative;
  left: 8vw;
  margin-top: 5%;
  transition: all ease-in-out 1s;
}
/* carousel */
.carousel {
  position: absolute;
  left: 4%;
  width: 70%;
  height: auto;
  display: flex;
  flex-direction: row;
  overflow: visible;
  justify-content: space-around;
}
/* general properties for images in the carousel */
.carousel img {
  height: 15vw;
  width: 22.5vw;
  transition: all cubic-bezier(0.68, -0.55, 0.265, 1.55) 0.2s;
}
/* first image in the carousel */
/* if you see it direction wise, then it is the third image in the carousel */
.carousel img:nth-child(1) {
  position: relative;
  left: 41vw;
  z-index: 2;
}
/* image which is in the maddle of the carousel */
.carousel img:nth-child(2) {
  z-index: 3;
}
/* third image in the carousel */
/* if you see it direction wise, then it is the first image in the carousel */
.carousel img:nth-child(3) {
  position: relative;
  right: 41vw;
  z-index: 1;
}

/* animations for carousel */

.carousel img:hover {
  z-index: 4;
  box-shadow: 0px 0px 12px 0.1px black;
  height: 18vw;
  width: 27vw;
}

/* latest release */

.latest-release {
  position: relative;
  top: 20vw;
  height: auto;
  width: 100%;
  box-sizing: border-box;
}
/* container of the latest release part should be of type flex */
.latest-release-content {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-around;
}
/* all the components of the latest release part */
.latest-release-content > div {
  /*  border:1px solid white; */
  height: 100px;
  width: 47%;
  margin: 5px 0px;
}
/* card is the general class for the components of the latest release part */
.card {
  display: flex;
  flex-direction: row;
  transition: box-shadow ease-in-out 0.1s;
}
/* hovering effects for the latest release part components */
.card:hover {
  box-shadow: 0px 0px 2px 1px white;
}
/* images in the cards of the latest release section */
.card img {
  width: 100px;
  height: 100px;
  z-index: 1;
}
/* this is the play button which will be visible only on hover */
.play-button {
  width: 100%;
  height: 65%;
  position: relative;
  top: -105%;
  color: rgba(255, 255, 255, 0);
  /* note that its opacity will be 0 normally */
  background-color: rgba(0, 0, 0, 0);
  font-size: 0px;
  padding-top: 15%;
  text-align: center;
  z-index: 5;
  transition: all ease-in-out 0.1s;
}
/* actual play icon from font awesome */
.play-button i {
  padding-top: 45%;
}
/* hovering effect for the play button */
.play-button:hover {
  color: rgba(255, 255, 255, 0.9);
  background-color: rgba(0, 0, 0, 0.5);
}
/* description of the song in the card, which will contain the song nae and author */
.song-description {
  margin: auto 10%;
}
/* options is the class for the 3 dots which needs to be clicked to trigger the latest release drop down menu */
.options {
  position: relative;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap-reverse;
  text-align: right;
  margin-left: auto;
  margin-right: 2%;
  margin-top: 2%;
}
/* this is for the latest release drop down menu */
.latest-release-dropdown {
  position: absolute;
  background-color: darkslateblue;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
  opacity: 0;
  width: 0px;
  height: 0px;
  top: 20px;
  right: 0px;
  overflow: hidden;
  z-index: 2;
  border: 1px solid black;
  box-shadow: 0px 0px 2px 1px black;
  transition: all ease-in-out 0.3s;
}
/* icon in the latest release drop down */
.fa-ellipsis-h {
  cursor: pointer;
}
/* this input is for the latest release drop down */
input[type="checkbox"] {
  display: none;
}
/* checking it, will trigger the latest release dropdown */
input[type="checkbox"]:checked ~ .latest-release-dropdown {
  width: max-content;
  height: auto;
  opacity: 1;
  padding: 5px;
}
/* options in the lastest release drop down */
.drop-item p {
  text-align: center;
}
/* popular artists */
.popular-artists {
  position: relative;
  width: 100%;
  height: auto;
  top: 26vw;
  box-sizing: border-box;
}
/* container of the popular artists */
.popular-artist-content {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
}
/* images in the popular artists section */
.popular-artists div a img {
  width: 10vw;
  min-width: 60px;
  min-height: 60px;
  height: 10vw;
  border-radius: 50%;
}
/* content of the container in popular artists section */
.popular-artists > div {
  /* position: relative; */
  margin: 5px;
  text-align: center;
}
/* I generally use the combination of 3 properties, i.e. display:flex, justify content and align items to position an element */
/* at the center of the screen. this is my favourite way. there are other options too, but I prefer this one because */
/* it also takes care of the flexibility of the contents of the div */
.popular-artist-content > a > div {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
}
.popular-artist-content > a > div > div {
  position: absolute;
  display: flex;
  /* top: 0px;
    left: 0px; */
  top: 0px;
  width: 10vw;
  min-width: 60px;
  min-height: 60px;
  height: 10vw;
  border-radius: 50%;
  background-color: rgb(0, 0, 0);
  opacity: 0;
  transition: opacity ease-in-out 0.1s;
}
/* additional icons in this section */
.popular-artist-content a div div i {
  margin: auto;
  font-size: 3vw;
  opacity: 0;
  transition: opacity ease-in-out 0.2s;
} /* added hovering effects */
.popular-artist-content a div div:hover {
  opacity: 0.5;
}
.popular-artist-content a div div:hover i {
  opacity: 1;
}
/* text portion in popular artists section */
.popular-artists div p {
  text-align: center;
}
/* music themes */
.music-themes {
  position: relative;
  top: 28vw;
  width: 100%;
  height: auto;
  box-sizing: border-box;
  background-image: var(--music-themes-background-image);
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  box-sizing: border-box;
}
/* stations */
.stations {
  margin-top: 30px;
  margin-bottom: 30px;
  margin-right: 10px;
}
/* these divs are for the colourful boxes in the themes section */
#div1 {
  width: 12vw;
  height: 8vw;
  background-color: darkslateblue;
}
#div2 {
  position: relative;
  top: -1vw;
  left: 1vw;
  width: 10vw;
  height: 10vw;
  background-color: lightgreen;
}
#div3 {
  position: relative;
  top: -1vw;
  left: 1vw;
  width: 8vw;
  height: 12vw;
  background-color: orange;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
/* logo in the outermost div */
#div3 img {
  width: 5vw;
  height: 5vw;
}
/* "stations" text */
#div3 p {
  font-size: 2vw;
}
/* images in the music themes section */
.music-themes div img {
  width: 8vw;
  height: 8vw;
  border-radius: 50%;
}
/* this is the sub content of the themes section */
.theme-content {
  margin: 3%;
  height: 8vw;
  width: 8vw;
  text-align: center;
  border-radius: 100%;
}
/* text within the themes section */
.theme-content p {
  text-align: center;
  position: relative;
  top: -8.25vw;
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 100%;
  font-size: 2vw;
  background-image: linear-gradient(
    0deg,
    rgb(201, 200, 185) -66%,
    rgba(0, 0, 0, 0)
  );
  transition: background-image 0.3s;
}
/* hovering effects on the contents of the divs inside the themes container */
.theme-content p:hover {
  background-image: linear-gradient(
    0deg,
    rgb(255, 50, 10) -66%,
    rgba(0, 0, 0, 0)
  );
}
/* container for theme contents */
.theme-main {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-around;
}

/* music themes -2 */
/* music themes has two parts the class with name just "music themes, is the uppper section with the gradient bakcground" */
/* this is the second section of music themes */
.music-themes-2 {
  position: relative;
  top: 30vw;
  height: auto;
  width: 100%;
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
}
/* this outer div contains the inner div and the image and text */
.outer-div {
  width: 19.5vw;
  height: 13vw;
  overflow: hidden;
  min-width: 123px;
  min-height: 82px;
  margin: 5px;
  cursor: pointer;
}
/* inner div portion */
.inner-div {
  width: 100%;
  height: 100%;
  background-color: black;
  background-position: center;
  background-size: cover;
  transition: all ease-in-out 0.3s;
}
/* divs corresponding to each of the 3 sub sections in the themes section */
/* party */
.music-themes-2 .outer-div:nth-child(1) .inner-div {
  background-image: url("media/music\ themes\ 2/party.jpg");
}
/* electronic */
.music-themes-2 .outer-div:nth-child(2) .inner-div {
  background-image: url("media/music\ themes\ 2/electronic.jpg");
}
/* road */
.music-themes-2 .outer-div:nth-child(3) .inner-div {
  background-image: url("media/music\ themes\ 2/road.jpg");
}
/* hivering actions: the text should be scaled down on hover and the background image should be scaled up at the same time gap */
.outer-div:hover .inner-div {
  transform: scale(1.3);
}
.outer-div .inner-div span {
  transform: scale(1);
  transition: all ease-in-out 0.3s;
}
.outer-div:hover .inner-div span {
  transform: scale(0.75);
}
.inner-div::before {
  content: "";
  display: none;
  height: 100%;
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
  transition: 0.3s;
}
/* adjusting inner div properties */
.inner-div {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.outer-div .inner-div span {
  /* color: white; */
  color: white;
  font-size: 2vw;
}

/* language wise */
/* language sections */
.language {
  position: relative;
  top: 31vw;
  height: auto;
  width: 100%;
  box-sizing: border-box;
  margin: 3vw 0px;
}
/* language content container */
.language-content {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: baseline;
  flex-wrap: wrap;
  padding: 0px 2px;
}
/* image in language content */
.language-content div img {
  width: 10vw;
  min-width: 60px;
  height: 10vw;
  min-height: 60px;
  transition: box-shadow ease-in-out 0.1s;
}
/* hovering effects on language content items */
.language-content div img:hover {
  box-shadow: 0px 0px 10px 1px white;
}
/* items in language content */
.language-content div {
  margin: 2vw 0px;
  width: 10.2vw;
  min-width: 60px;
}
/* properties for release date and name of the song */
.language-content div p:nth-child(2n) {
  width: 100%;
  word-wrap: break-word;
}
.language-content div p:nth-child(2n + 1) {
  font-size: 12px;
  font-weight: lighter;
}
/* ////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// */
/* section 2 starts here */
/* #007bff */
/* more button */
label[for="more"] {
  display: none;
  position: absolute;
  right: 0%;
  top: 20%;
  padding-bottom: 5px;
  z-index: 4;
  width: 70px;
  font-size: 20px;
  height: 25px;
  text-align: center;
  box-shadow: 0px 0px 2px 1px white;
  background-image: linear-gradient(45deg, red -50%, blue 150%);
}
/* when the checkbox corresponding to the "more" button is checked, then the section becomes visible */
/* but at a normal resolution, its display will be none */
label[for="more"]:checked ~ input {
  display: none;
}
/* ASIDE SECTION 2 */
.heading {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: baseline;
  margin-bottom: 12%;
}
/* heading for the second  aside section */
.heading h4 a {
  text-decoration: none;
  color: greenyellow;
}
/* these are the properties for the queue options box. the queue options box will be visible when one clicks on the queue button */
.queue-options {
  position: fixed;
  right: 4%;
  top: 14%;
  background-color: #f8f9fa;
  width: 10%;
  height: auto;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  padding: 1%;
  box-sizing: border-box;
  overflow: hidden;
  z-index: 2; /* to cover the heart icon */
  opacity: 0;
  transform: scale(0);
  transition: all ease-in-out 0.25s;
}
/* when the queue option box becomes target */
#queue-option-box:target {
  opacity: 1;
  transform: scale(1);
}
.queue-options {
  color: black;
}
.queue-options p {
  text-align: center;
}
.queue-options p a {
  text-decoration: none;
}
/* horizontal line in queue options box */
hr {
  width: 90%;
  color: black;
}

/* playlist content */
.playlist-content {
  width: 100%;
  height: 75vh;
  /*     margin-top:4vh; */
  display: flex;
  flex-direction: column;
  overflow: scroll;
  cursor: pointer;
}
/* playlist content container scroll bar */
.playlist-content::-webkit-scrollbar {
  display: none;
}
/* left content contains the image, index and name of the song */
.left-content {
  display: flex;
  height: 100%;
  width: 70%;
  flex-direction: row;
  flex-wrap: no-wrap;
  justify-content: space-between;
  align-items: center;
}
.left-content > div:nth-child(3) {
  margin-left: 12px;
  width: 50%;
  word-wrap: break-word;
}
/* right content contains the heart icon */
.right-content {
  position: relative;
  bottom: 62%;
  left: 90%;
  width: min-content;
  height: 20px;
  color: white;
  font-size: 20px;
}
.right-content i {
  transition: all ease-in-out 0.1s;
}
.right-content i:hover {
  color: red;
}
/* class for a partilcular item in playlist */
.playlist-item {
  width: 90%;
  height: auto;
  padding: 0px 1%;
  box-sizing: border-box;
  margin: 1%;
  /* transition: all ease-in-out 0.1s; */
}
/* animation for glowing heart in each of the playlist items */
@keyframes glowing-heart {
  0% {
    color: yellow;
  }
  50% {
    color: orangered;
  }
  100% {
    color: red;
  }
}
/* hover effect on heart */
.playlist-item:hover .fa-heart {
  animation-name: glowing-heart;
  animation-iteration-count: infinite;
  animation-direction: alternate;
  animation-duration: 1s;
}
/* playlist items hovering effect */
.playlist-item:hover {
  box-shadow: 0px 0px 2px 1px white;
}
/* playlist item image */
.playlist-item img {
  width: 80px;
  height: 80px;
}
/* this will cover the playlist image. this can be called as a container for half of the items in the left part */
.coverer {
  width: 80px;
  height: 80px;
}
/* ////////////////////////////////////////////////////////////////////////////////////////////////////////////// */

/* Footer section starts here*/
/* this is the container for the whole footer */
footer {
  position: absolute;
  bottom: 1px;
  width: 100%;
  height: 60px;
  background-color: #282828;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-content: center;
  flex-wrap: nowrap;
  padding: 0px 3%;
  box-sizing: border-box;
  z-index: 6;
}
/* footer is divided into 3 parts */
/* 1. first part of the footer */
.active-song-description {
  /* border:1px solid white; */
  height: 90%;
  width: 25%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
}
/* the current song which is being played, this is the image container for that. */
#song-image {
  width: 50px;
  height: 50px;
  min-width: 50px;
  min-height: 50px;
}
/* current song image */
#song-image img {
  width: 100%;
  height: 100%;
}
/* heart and ban icon */
.heart-and-ban-icon {
  height: 100%;
  padding-top: 4%;
}
/* song decscription */
.song-desc {
  margin-right: 1%;
  margin-left: 1%;
}
/* song name */
.song-desc div:nth-child(1) {
  font-size: 14px;
}
/* song author */
.song-desc div:nth-child(2) {
  font-size: 12px;
}

/* 2. Second part of the footer*/
.player {
  width: 45%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  flex-wrap: nowrap;
}
/* controls is the container for all the center controls of the player */
.controls {
  width: 40%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  font-size: 20px;
}
/* this is the song-duration slider */
#slider {
  width: 100%;
  font-size: 12px;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  align-items: center;
  justify-content: center;
  margin-top: 5px;
}
/* ////////// */
.time {
  margin: 0px 10px;
}

/* adjusting the slider for better visuals */
.slidecontainer {
  width: 100%;
}
/* for audio and main center player */
.slider {
  -webkit-appearance: none;
  width: 100%;
  height: 5px;
  background: #d3d3d3;
  outline: none;
  opacity: 0.5;
  -webkit-transition: 0.2s;
  transition: opacity 0.2s;
}
/* hover effect for the slider */
.slider:hover {
  opacity: 1;
}
/* these are for adjusting the dimensions and default styling of the long-slider */
.slider::-webkit-slider-thumb {
  -webkit-appearance: none;
  appearance: none;
  width: 17px;
  height: 17px;
  border-radius: 50%;
  background: #007bff;
  cursor: pointer;
}
/* this is the circular thumb, which can be moved across the div */
.slider::-moz-range-thumb {
  width: 25px;
  height: 25px;
  background: #4caf50;
  cursor: pointer;
}

/* third part of the footer */
/* this contains the extra icons and slider for volume */
/* this is also a container */
.extras {
  width: 20%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
}




single playlist html 






<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Adarsh Playlist</title>
    <!-- it is connected to two stylesheets -->
    <link
      rel="stylesheet"
      type="text/css"
      href="SinglePlaylistScreenStyle.css"
    />
    <!-- this is the main stylesheet -->
    <!-- desktop first approach is used for the same. -->
    <link rel="stylesheet" type="text/css" href="Secondarypageresponsive.css" />
    <!-- this is the style sheet with all the media queries -->
    <!-- this script is just for font awesome fonts -->
    <script
      src="https://kit.fontawesome.com/2d9b67a497.js"
      crossorigin="anonymous"
    ></script>
  </head>
  <!-- body -->

  <body>
    <!-- top navigation bar -->
    <nav class="navigation-bar">
      <!-- this div contains the logo and title os the page -->
      <div class="title-combo">
        <div class="website-logo">
          <img src="media/website_logo.png" />
        </div>
        <div class="website-name">
          <h2>
            <a href="index.html">
              Anil
            </a>
          </h2>
          <h6 style="color: magenta;">
            <a href="index.html">Music Player</a>
          </h6>
        </div>
      </div>
      <!-- this is the animated favourites text -->
      <div class="favs">
        <h4>
          Favourites
        </h4>
      </div>
      <div class="search-bar">
        <div>
          <!-- magnifying glass- search icon -->
          <i class="fas fa-search search-ico"></i>
        </div>
        <input type="text" name="search" placeholder="Search" />
        <div>
          <!-- mic icon -->
          <i class="fas fa-microphone mic-ico"></i>
        </div>
      </div>
      <!-- this is for notification bell -->
      <div class="notification-bell">
        <img src="media/bell_icon.png" /> Notifications
      </div>
      <!-- this is for profile picture -->
      <div class="profile-picture">
        <img src="media/profile_picture.png" />
      </div>
    </nav>
    <!-- this is the main center part of the page and it is divided into two sections, namely section 1 and section 2-->
    <!-- I have separated these sections using the aside tag for each section -->
    <main>
      <!-- aside section 1 -->
      <aside class="aside section-1">
        <!-- this is for the jumbotron -->
        <div class="jumbotron">
          <div class="jumbotron-image">
            <!-- there is nothing in this div because all the images and all are added by css -->
          </div>
          <!-- jumbotron details -->
          <div class="jumbotron-detail">
            <!-- descriptive part of the jumbotron this will contain name , number of followers and all -->
            <div class="descriptive-part">
              <div class="song-name-main">
                <h1>ColdPlay</h1>
              </div>
              <div class="followers">
                21m Followers
              </div>
              <p class="author">British Band</p>
              <!-- short description of the current author -->
              <p class="desc">
                Coldplay are a British rock band formed in London in 1996.
                Vocalist, rhythm guitarist and pianist Chris Martin, lead
                guitarist Jonny Buckland, bassist Guy Berryman, and drummer Will
                Champion met at University College London and began playing
                music together from 1996 to 1998, first calling themselves
                Pectoralz and then Starfish before finally changing their name
                to Coldplay
              </p>
            </div>
            <!-- action part -->
            <div class="action-part">
              <!-- action buttons -->
              <div class="btns">
                <button>Play All</button>
                <button>Follow</button>
              </div>
              <p>
                247 Tracks | 128 Albums
              </p>
            </div>
          </div>
        </div>
        <!-- now the playlist part begins -->
        <div class="playlist-items">
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                01
              </div>
              <div>
                <img
                  src="media/playlist/austin-neill-kKlVSrFbjYY-unsplash.jpg"
                />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Alone
                </h5>
                <p>
                  Alan Walker
                </p>
              </div>
            </div>
            <div class="center">
              3:14
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                02
              </div>
              <div>
                <img src="media/playlist/stoney.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  White Iverson
                </h5>
                <p>
                  Post Malone
                </p>
              </div>
            </div>
            <div class="center">
              3:44
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                03
              </div>
              <div>
                <img src="media/playlist/stoney.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Go Flex
                </h5>
                <p>
                  Post Malone
                </p>
              </div>
            </div>
            <div class="center">
              2:55
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                04
              </div>
              <div>
                <img src="media/playlist/stoney.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Better Now
                </h5>
                <p>
                  Post Malone
                </p>
              </div>
            </div>
            <div class="center">
              3:37
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                05
              </div>
              <div>
                <img src="media/playlist/stoney.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Big lie
                </h5>
                <p>
                  Post Malone
                </p>
              </div>
            </div>
            <div class="center">
              3:27
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                06
              </div>
              <div>
                <img src="media/playlist/stoney.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Deja Vu
                </h5>
                <p>
                  Post Malone & Justin Beiber
                </p>
              </div>
            </div>
            <div class="center">
              4:31
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                07
              </div>
              <div>
                <img src="media/playlist/beer.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Pysco
                </h5>
                <p>
                  Post Malone
                </p>
              </div>
            </div>
            <div class="center">
              3:28
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                08
              </div>
              <div>
                <img src="media/playlist/beer.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Rockstar
                </h5>
                <p>
                  Post Malone & 21 Savage
                </p>
              </div>
            </div>
            <div class="center">
              3:48
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                09
              </div>
              <div>
                <img src="media/playlist/after.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Blinding Lights
                </h5>
                <p>
                  Weeknd
                </p>
              </div>
            </div>
            <div class="center">
              3:20
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                10
              </div>
              <div>
                <img src="media/playlist/after.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Alone Again
                </h5>
                <p>
                  Weeknd
                </p>
              </div>
            </div>
            <div class="center">
              4:10
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                11
              </div>
              <div>
                <img src="media/playlist/after.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Too Late
                </h5>
                <p>
                  Weeknd
                </p>
              </div>
            </div>
            <div class="center">
              4:00
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
          <!-- playlist item -->
          <div class="playlist-item">
            <div class="left">
              <div>
                12
              </div>
              <div>
                <img src="media/playlist/after.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div>
                <h5>
                  Hardest To Love
                </h5>
                <p>
                  Weeknd
                </p>
              </div>
            </div>
            <div class="center">
              3:31
            </div>
            <div class="right">
              <div>
                <i class="far fa-heart"></i>
              </div>
              <div>
                <i class="fas fa-plus"></i>
              </div>
            </div>
          </div>
        </div>
      </aside>
      <!-- one aside section is complete -->
      <!-- now the second aside section will start from here -->
      <!-- the page is responsive. please try reducing the width of the page -->
      <!-- the aside section will collapse and a "more button will be shown to you." -->
      <!-- clicking on this more button, you will be shown the aside section 2  -->
      <!-- its position will be absolute at lower resolutions -->
      <!-- this is the label for that more button -->
      <label for="more"><i class="fas fa-angle-double-left"></i>More</label>
      <!-- this is that more button -->
      <!-- and this is the check box. this will always be hidden -->
      <!-- check the stylesheet_main.css when the label is clicked, this checkbox will be checked -->
      <!-- which will invoke the aside section 2 on lower resolutions -->
      <input type="checkbox" id="more" />
      <!-- </div> -->
      <aside class="aside section-2">
        <!-- similar class will be applicable to both similar artists and recently played -->
        <div class="similar">
          <!-- section heading, which also contains the view all button -->
          <div class="section-heading">
            <h1>Similar Artists</h1>
            <div class="view-all-button">
              View All
            </div>
          </div>
          <!-- list is the container for the contents of similar artists -->
          <div class="list">
            <!-- item -->
            <div class="list-item">
              <div>
                <img src="media/music themes/love.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div style="position: absolute; left: 120px;">
                <h5>
                  Love me
                </h5>
                <p class="author-name">
                  Justin Beiber
                </p>
              </div>
              <div class="extra">
                <div>
                  <i class="fas fa-ellipsis-h"></i>
                </div>
                <p class="author-name">
                  2:14
                </p>
              </div>
            </div>
            <!-- item -->
            <div class="list-item">
              <div>
                <img src="media/popular artists/sixnine.jpg" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div style="position: absolute; left: 120px;">
                <h5>
                  Gotti
                </h5>
                <p class="author-name">
                  6ix9ine
                </p>
              </div>
              <div class="extra">
                <div>
                  <i class="fas fa-ellipsis-h"></i>
                </div>
                <p class="author-name">
                  4:00
                </p>
              </div>
            </div>
            <!-- item -->
            <div class="list-item">
              <div>
                <img src="media/songs/shit.png" />
                <div class="play-btn">
                  <i class="fas fa-play"></i>
                </div>
              </div>
              <div style="position: absolute; left: 120px;">
                <h5>
                  WAP
                </h5>
                <p class="author-name">
                  Cardi B
                </p>
              </div>
              <div class="extra">
                <div>
                  <i class="fas fa-ellipsis-h"></i>
                </div>
                <p class="author-name">
                  4:44
                </p>
              </div>
            </div>
          </div>

          <!-- recently played section -->
          <div class="similar">
            <!-- section headings, which also contains the view all button -->
            <div class="section-heading">
              <h1>Recently Played</h1>
              <div class="view-all-button">
                View All
              </div>
            </div>
            <!-- again list is a container for all the contents of recently played section -->
            <div class="list">
              <!-- item -->
              <div class="playlist-item">
                <div class="left">
                  <div>
                    01
                  </div>
                  <div>
                    <img src="media/latest english/I'll Wait.jpg" />
                    <div class="play-btn">
                      <i class="fas fa-play"></i>
                    </div>
                  </div>
                  <div>
                    <h5>
                      I'll wait
                    </h5>
                    <p>
                      Kygo
                    </p>
                  </div>
                </div>
                <div class="right">
                  <div>
                    <i class="far fa-heart"></i>
                  </div>
                </div>
              </div>
              <!-- item -->
              <div class="playlist-item">
                <div class="left">
                  <div>
                    02
                  </div>
                  <div>
                    <img src="media/latest english/let me go.jpg" />
                    <div class="play-btn">
                      <i class="fas fa-play"></i>
                    </div>
                  </div>
                  <div>
                    <h5>
                      Let Me Go
                    </h5>
                    <p>
                      NoMethod
                    </p>
                  </div>
                </div>
                <div class="right">
                  <div>
                    <i class="far fa-heart"></i>
                  </div>
                </div>
              </div>
              <!-- item -->
              <div class="playlist-item">
                <div class="left">
                  <div>
                    03
                  </div>
                  <div>
                    <img src="media/latest english/ily.jpg" />
                    <div class="play-btn">
                      <i class="fas fa-play"></i>
                    </div>
                  </div>
                  <div>
                    <h5>
                      ILY
                    </h5>
                    <p>
                      Surf Mesa
                    </p>
                  </div>
                </div>
                <div class="right">
                  <div>
                    <i class="far fa-heart"></i>
                  </div>
                </div>
              </div>
              <!-- item -->
              <div class="playlist-item">
                <div class="left">
                  <div>
                    04
                  </div>
                  <div>
                    <img src="media/latest english/roar.jpg" />
                    <div class="play-btn">
                      <i class="fas fa-play"></i>
                    </div>
                  </div>
                  <div>
                    <h5>
                      Roar
                    </h5>
                    <p>
                      Ketty Perry
                    </p>
                  </div>
                </div>
                <div class="right">
                  <div>
                    <i class="far fa-heart"></i>
                  </div>
                </div>
              </div>
              <!-- item -->
              <div class="playlist-item">
                <div class="left">
                  <div>
                    05
                  </div>
                  <div>
                    <img src="media/latest english/toosie slide.jpg" />
                    <div class="play-btn">
                      <i class="fas fa-play"></i>
                    </div>
                  </div>
                  <div>
                    <h5>
                      Toosie Slide
                    </h5>
                    <p>
                      Drake
                    </p>
                  </div>
                </div>
                <div class="right">
                  <div>
                    <i class="far fa-heart"></i>
                  </div>
                </div>
              </div>
              <!-- item -->
              <div class="playlist-item">
                <div class="left">
                  <div>
                    06
                  </div>
                  <div>
                    <img src="media/latest english/uptown funk.png" />
                    <div class="play-btn">
                      <i class="fas fa-play"></i>
                    </div>
                  </div>
                  <div>
                    <h5>
                      Uptwon Funk
                    </h5>
                    <p>
                      Bruno
                    </p>
                  </div>
                </div>
                <div class="right">
                  <div>
                    <i class="far fa-heart"></i>
                  </div>
                </div>
              </div>
              <!-- item -->
              <div class="playlist-item">
                <div class="left">
                  <div>
                    07
                  </div>
                  <div>
                    <img src="media/latest hindi/baarish.jpeg" />
                    <div class="play-btn">
                      <i class="fas fa-play"></i>
                    </div>
                  </div>
                  <div>
                    <h5>
                      Baarish
                    </h5>
                    <p>
                      Half Girlfriend
                    </p>
                  </div>
                </div>
                <div class="right">
                  <div>
                    <i class="far fa-heart"></i>
                  </div>
                </div>
              </div>
              <!-- item -->
              <div class="playlist-item">
                <div class="left">
                  <div>
                    08
                  </div>
                  <div>
                    <img src="media/latest hindi/galiyaan.jpg" />
                    <div class="play-btn">
                      <i class="fas fa-play"></i>
                    </div>
                  </div>
                  <div>
                    <h5>
                      Gulliyon
                    </h5>
                    <p>
                      Ek Villan
                    </p>
                  </div>
                </div>
                <div class="right">
                  <div>
                    <i class="far fa-heart"></i>
                  </div>
                </div>
              </div>
              <!-- item -->
              <div class="playlist-item">
                <div class="left">
                  <div>
                    09
                  </div>
                  <div>
                    <img src="media/latest hindi/giveme some sunshine.jpg" />
                    <div class="play-btn">
                      <i class="fas fa-play"></i>
                    </div>
                  </div>
                  <div>
                    <h5>
                      All-is-well
                    </h5>
                    <p>
                      3idiots
                    </p>
                  </div>
                </div>
                <div class="right">
                  <div>
                    <i class="far fa-heart"></i>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </aside>
    </main>

    <!-- main part of the page is over. -->
    <!-- this is the footer part. -->
    <!-- its position will be fixed to the screen bottom. -->
    <footer>
      <div class="active-song-description">
        <!-- song image -->
        <div id="song-image">
          <img src="media/playlist/stoney.jpg" />
        </div>
        <!-- song name and author -->
        <div class="song-desc">
          <div>
            White Iverson
          </div>
          <div>
            Post Malone
          </div>
        </div>
        <!-- heart icon and ban icon -->
        <div class="heart-and-ban-icon">
          <span>
            <i class="far fa-heart"></i>
          </span>
          <span>
            <i class="fas fa-ban"></i>
          </span>
        </div>
      </div>
      <!-- these are the main player controls -->
      <div class="player">
        <div class="controls">
          <div><i class="fas fa-random"></i></div>
          <div><i class="fas fa-step-backward"></i></div>
          <div><i class="fas fa-pause-circle"></i></div>
          <div><i class="fas fa-step-forward"></i></div>
          <div><i class="fas fa-redo"></i></div>
        </div>
        <!-- this is the slider -->
        <div id="slider">
          <!-- current time -->
          <div class="time">
            1:39
          </div>
          <div class="slidecontainer">
            <input
              type="range"
              min="0"
              max="100"
              value="0"
              class="slider"
              id="myRange"
            />
          </div>
          <!-- total time -->
          <div class="time">
            4:44
          </div>
        </div>
      </div>
      <!-- other icons including the volume slider and all -->
      <div class="extras">
        <div>
          <i class="fas fa-list-ul"></i>
        </div>
        <div>
          <i class="fas fa-laptop"></i>
        </div>
        <div>
          <i class="fas fa-volume-up"></i>
        </div>
        <div class="slidecontainer" style="width: 30%;">
          <input
            type="range"
            min="0"
            max="100"
            value="0"
            class="slider"
            id="myRange"
            style="margin-top: 0px;"
          />
        </div>
        <div>
          <i class="fas fa-expand-alt"></i>
        </div>
      </div>
    </footer>
  </body>
</html>

 
 
 
