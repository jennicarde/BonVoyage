=============

1. Navigation hover effect (lines 6-15)
2. Images hover effect (lines 21-73)
3. Social Media Icons transition effect (lines 76-188)

=============


1. Navigation hover effect
  <nav class="cl-effect-5 quicksand" id="cl-effect-5">
    <ul class="menu">

      <li><a href="#"><span data-hover="Home">Home</span></a></li>
      <li><a href="#about"> <span data-hover="Our Story">Our Story</span></a></li>
       <li><a href="#destinations"><span data-hover="Destinations">  Destinations</span></a></li>
      <li><a href="#contact"><span data-hover="Contact Us"> Contact Us</span></a></li>
    </ul>
  </nav>

2. Images hover effect
  <div class="jm-mainpage-box">

            <!-- thumbnail -->
             <div class="jm-item first">
              <div class="jm-item-wrapper">
                <div class="jm-item-image">
                    <img src="http://lorempixel.com/245/170/city/4/" alt="Travel Destination" />
                  <span class="jm-item-overlay"> </span>
                  <div class="jm-item-button"><a href="#">View</a></div>
                </div>  
                <div class="jm-item-title">New York, USA</div>
              </div>
            </div>
    

            <!-- thumbnail -->
            <div class="jm-item first">
              <div class="jm-item-wrapper">
                <div class="jm-item-image">
                    <img src="http://lorempixel.com/245/170/city/2/" alt="Travel Destination" />
                  <span class="jm-item-overlay"> </span>
                  <div class="jm-item-button"><a href="#">View</a></div>
                </div>  
                <div class="jm-item-title">Vegas, USA</div>
              </div>
            </div>     

            <!-- thumbnail -->
            <div class="jm-item first">
              <div class="jm-item-wrapper">
                <div class="jm-item-image">
                    <img src="http://lorempixel.com/245/170/city/9/" alt="Travel Destination" />
                  <span class="jm-item-overlay"> </span>
                  <div class="jm-item-button"><a href="#">View</a></div>
                </div>  
                <div class="jm-item-title">SF, USA</div>
              </div>
            </div>    

            <!-- thumbnail -->
            <div class="jm-item first">
              <div class="jm-item-wrapper">
                <div class="jm-item-image">
                    <img src="http://lorempixel.com/245/170/city/7/" alt="Travel Destination" />
                  <span class="jm-item-overlay"> </span>
                  <div class="jm-item-button"><a href="#">View</a></div>
                </div>  
                <div class="jm-item-title">Sidney, Australia</div>
              </div>
            </div>   

      </div><!--End thumbnails -->


 3. Social Media Icons transition effect 
  <!-- Contact section & social icons -->
  HTML markup:
  <section id="contact" class="box">
    <h2>Contact Us or <em>Travel</em> with Us</h2>
    <ul class='socials'>
      <li><a class='twitter' href="https://twitter.com"></a></li>
      <li><a class='facebook' href="https://facebook.com"></a></li>
      <li><a class='linkedin' href="https://linkedin.com"></a></li>
    </ul>   
  </section>


  /==== *Social media icons - COLORS* ====/
  a.github {
   background: url(../images/social_media.png) left top;
  }
    section#contact li:hover a.github{
    background: url(../images/social_media.png) left bottom;
    }

  a.wordpress {
   background: url(../images/social_media.png) -128px top;
  }
    section#contact li:hover a.wordpress {
    background: url(../images/social_media.png) -128px bottom;
    }

  a.fb {
   background: url(../images/social_media.png) -256px top;
  }
    section#contact li:hover a.fb {
    background: url(../images/social_media.png) -256px bottom;
    }

  a.linkedin {
   background: url(../images/social_media.png) -384px top;
  }
    section#contact li:hover a.linkedin {
    background: url(../images/social_media.png) -384px bottom;
    }

  a.twitter {
   background: url(../images/social_media.png) -512px top;
  }
    section#contact li:hover a.twitter {
    background: url(../images/social_media.png) -512px bottom;
    }

  a.youtube {
   background: url(../images/social_media.png) -640px top;
  }
    section#contact li:hover a.youtube {
    background: url(../images/social_media.png) -640px bottom;
    }

  a.googleplus {
   background: url(../images/social_media.png) -768px top;
  }
    section#contact li:hover a.googleplus {
    background: url(../images/social_media.png) -768px bottom;
    }


  /==== *Social media icons - GRADIENT * ====/
  a.github {
   background: url(../images/social_media_gradient.png) left top;
  }
    section#contact li:hover a.github{
    background: url(../images/social_media_gradient.png) left bottom;
    }

  a.wordpress {
   background: url(../images/social_media_gradient.png) -128px top;
  }
    section#contact li:hover a.wordpress {
    background: url(../images/social_media_gradient.png) -128px bottom;
    }

  a.fb {
   background: url(../images/social_media_gradient.png) -256px top;
  }
    section#contact li:hover a.fb {
    background: url(../images/social_media_gradient.png) -256px bottom;
    }

  a.linkedin {
   background: url(../images/social_media_gradient.png) -384px top;
  }
    section#contact li:hover a.linkedin {
    background: url(../images/social_media_gradient.png) -384px bottom;
    }

  a.twitter {
   background: url(../images/social_media_gradient.png) -512px top;
  }
    section#contact li:hover a.twitter {
    background: url(../images/social_media_gradient.png) -512px bottom;
    }

  a.youtube {
   background: url(../images/social_media_gradient.png) -640px top;
  }
    section#contact li:hover a.youtube {
    background: url(../images/social_media_gradient.png) -640px bottom;
    }

  a.googleplus {
   background: url(../images/social_media_gradient.png) -768px top;
  }
    section#contact li:hover a.googleplus {
    background: url(../images/social_media_gradient.png) -768px bottom;
    }

