# HTML-CSS-one-page-website Space Station themed HTML/CSS One Page Website
<head>
  <meta charset="utf-8">
  <title>The Voyager Space Station | Resort</title>
  <link rel="stylesheet" href="./SSW_CSS/shared.css">
  <link rel="stylesheet" href="./SSW_CSS/animations.css">
</head><!-- NAV -->
<div class="wrap">
  <div class="menu-container">
    <ul class="menu">
      <a href="#home" id="link"></a>
      <li>HOME</li><a href="#gallery" id="link"></a>
      <li>GALLERY</li><a href="#contact" id="link"></a>
      <li>RESERVATIONS</li>
    </ul>
  </div>
</div><!-- END NAV -->
<!-- HOME -->
<div id="home">
  <div class="container">
    <div class="text-center">
      <span class="head-main">The Voyager Space Station</span>
    </div>
  </div>
</div><!-- END HOME -->
<!-- GALLERY -->
<section id="gallery">
  <div class="container">
    <h1>Gallery</h1>
    <div class="flex-container">
      <!-- PHOTO-CONTAINER 1 -->
      <div class="photo-container">
        <div class="photo">
          <img src="./SSW_Images/SSW_Thumbs/thumbnail_1.jpg" alt="A manned rocketship continues its vertical ascent after breaking through heavy cloud cover">
          <div class="photo-overlay">
            <h3>Click to Enlarge</h3>
            <p>We have several space launches departing <em><u>daily</u></em> - book your flight today!</p>
          </div>
        </div>
      </div><!-- END PHOTO-CONTAINER-1 -->
      <!-- PHOTO-CONTAINER 2 -->
      <div class="photo-container">
        <div class="photo">
          <img src="./SSW_Images/SSW_Thumbs/thumbnail_2.jpg" alt="Voyager Station - The World's First Space Hotel, opening 2027 | Architectural Digest">
          <div class="photo-overlay">
            <h3>Click to Enlarge</h3>
            <p>Voyager Station is the world's first Space Hotel, opening 2027</p>
          </div>
        </div>
      </div><!-- END PHOTO-CONTAINER-2 -->
      <!-- PHOTO-CONTAINER 3 -->
      <div class="photo-container">
        <div class="photo">
          <img src="./SSW_Images/SSW_Thumbs/thumbnail_3.jpg" alt="Typical space station accommodations are similar to traditional terrestrial hotels, but offer panoramic views of Earth">
          <div class="photo-overlay">
            <h3>Click to Enlarge</h3>
            <p>Let each day begin with stunningly beautiful, paroramic views of Earth</p>
          </div>
        </div>
      </div><!-- END PHOTO-CONTAINER-3 -->
      <!-- PHOTO-CONTAINER 4 -->
      <div class="photo-container">
        <div class="photo">
          <img src="./SSW_Images/SSW_Thumbs/thumbnail_4.jfif" alt="A horizontal wireframe image of the Voyager Station">
          <div class="photo-overlay">
            <h3>Click to Enlarge</h3>
            <p>Diligently designed to enhance your safety, comfort, & convenience</p>
          </div>
        </div>
      </div><!-- END PHOTO-CONTAINER-4 -->
      <!-- PHOTO-CONTAINER 5 -->
      <div class="photo-container">
        <div class="photo">
          <img src="./SSW_Images/SSW_Thumbs/thumbnail_5.jpg" alt="A highly detailed, interior rendering of a starship's conference room/observation lounge, by MCH of cgtrader.com">
          <div class="photo-overlay">
            <h3>Click to Enlarge</h3>
            <p>Premium lounge areas await your arrival, outfitted with the advanced surroundings you deserve</p>
          </div>
        </div>
      </div><!-- END PHOTO-CONTAINER-5 -->
      <!-- PHOTO-CONTAINER 6 -->
      <div class="photo-container">
        <div class="photo">
          <img src="./SSW_Images/SSW_Thumbs/thumbnail_6.jpg" alt="A 3D model of a future space station, courtesy of done3d.com">
          <div class="photo-overlay">
            <h3>Click to Enlarge</h3>
            <p>Whether stationary or mobile, each space station in our fleet can easily fulfill your dreams</p>
          </div>
        </div>
      </div><!-- END PHOTO-CONTAINER-6 -->
      <!-- PHOTO-CONTAINER 7 -->
      <div class="photo-container">
        <div class="photo">
          <img src="./SSW_Images/SSW_Thumbs/thumbnail_7.jpg" alt="A futuristic 2100 ISS concept, by Madalin Croitoru, Lead Artist @ EVL PPY">
          <div class="photo-overlay">
            <h3>Click to Enlarge</h3>
            <p>Reserve your spacious accommodations aboard our newest, Year 2100 space station now</p>
          </div>
        </div>
      </div><!-- END PHOTO-CONTAINER-7 -->
      <!-- PHOTO-CONTAINER 8 -->
      <div class="photo-container">
        <div class="photo">
          <img src="./SSW_Images/SSW_Thumbs/thumbnail_8.jpg" alt="A futuristic space station, designed &amp; rendered with Cinema 4D R16, by Johann deLestree">
          <div class="photo-overlay">
            <h3>Click to Enlarge</h3>
            <p>Redefining your perceptions of luxury, serenity, & uniqueness, then surpassing those expectations</p>
          </div>
        </div>
      </div><!-- END PHOTO-CONTAINER-8 -->
      <!-- PHOTO-CONTAINER 9 -->
      <div class="photo-container">
        <div class="photo">
          <img src="./SSW_Images/SSW_Thumbs/thumbnail_9.jpg" alt="A 3D visualization of a rotating orbital space station, by Kresimir Jelusic">
          <div class="photo-overlay">
            <h3>Click to Enlarge</h3>
            <p>Explore the wonders of space aboard these fascinating wonders of mankind</p>
          </div>
        </div>
      </div><!-- END PHOTO-CONTAINER-9 -->
    </div>
  </div>
</section><!-- END GALLERY -->
<!-- RSVP -->
<section id="contact">
  <div class="container">
    <div class="heading-padding">
      <h1 class="heading-padding">Reservations</h1>
      <div class="reservation">
        <h2><span>Your adventure is just around the moon.</span><br>
        Reserve your flight today!</h2>
        <p class="rsvp-text">Please provide us with your basic contact information.</p>
        <div class="form-rsvp">
          <form action="" method="post">
            <input class="rsvp" type="text" value="" placeholder="First Name"> <input class="rsvp" type="text" value="" placeholder="Last Name"> <input class="rsvp" type="text" value="" placeholder="Email Address"> <input class="rsvp" type="text" value="" placeholder="Phone Number"> <input class="rsvp" type="text" value="" placeholder="Number of guests">
            <div class="form-spacer">
              <label class="terms">Terms and Conditions</label>
            </div>
            <div class="submit">
              <input type="submit" value="Submit">
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</section><!-- END RSVP -->
<!-- FOOTER -->
<footer class="footer">
  <div id="footer1">
    <a href="https://theconversation.com/space-tourism-20-years-in-the-making-is-finally-ready-for-launch-159606?utm_medium=email&amp;utm_campaign=Saturday%20Newsletter%20%20May%201%202021%20-%201935718946&amp;utm_content=Saturday%20Newsletter%20%20May%201%202021%20-%201935718946+CID_1b0ff8a2f642c814f88f78e554e224a8&amp;utm_source=campaign_monitor_us&amp;utm_term=Space%20tourism%20%2020%20years%20in%20the%20making%20%20is%20finally%20ready%20for%20launch" target="new">From Humble Beginnings...</a>
  </div><a href="#home">www.theVoyagerSpaceStation.space</a> &nbsp;|&nbsp; © 2021
</footer><!-- END FOOTER -->

