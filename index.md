<!DOCTYPE html>
<html lang="en">
<head>
    <!-- META TAGS -->
    <meta charset="utf-8">
    <meta name="author" content="AtypicalThemes">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1"> 

    <!-- WEBSITE TITLE & DESCRIPTION -->
    <title>Oddmar - An Adventure Game</title>
    <meta name="description" content="AN IMMERSIVE ADVENTURE GAME, NOW AVAILABLE IN BETA.">
    <meta name="keywords" content="game, gaming, videogame, developer, steam, studio, team">

    <!-- OG meta tags that improve the look of your post on social media -->
    <meta property="og:site_name" content="">
    <meta property="og:site" content=""> <!--website link-->
    <meta property="og:title" content="">
    <meta property="og:description" content="">
    <meta property="og:image" content=""><!-- Image link (jpg only)-->
    <meta property="og:url" content=""> <!--where do you want your post to link to-->
    <meta property="og:type" content="article">

    <!-- Favicon and Apple Icons -->
    <link rel="icon" type="image/png" sizes="16x16" href="images/logochico.png">

    <!-- STYLES -->
    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <!-- FontAwesome -->
    <link href="css/font-awesome.min.css" rel="stylesheet">
    <!-- Animations -->
    <link href="css/animations.css" rel="stylesheet">
    <!-- Lightbox -->
    <link href="css/lightbox.min.css" rel="stylesheet">
    <!-- Video Lightbox -->
    <link href="css/modal-video.min.css" rel="stylesheet">
    <!-- Main Stylesheet -->
    <link href="css/style.css" rel="stylesheet">
  
</head>
<body>
    <!-- Loading Screen -->
    <div id="loader-wrapper">
        <h1 class="loader-logo"><span class="colored">O</span>DDMAR</h1>
        <div id="progress"></div>
        <h3 class="loader-text">LOADING</h3>
    </div>
    
    <!-- //// HEADER //// -->
    <header id="main-header">
        <nav class="navbar fixed-top navbar-expand-lg navbar-dark">
            <div class="container">
                <!-- Site Logo -->
                <a id="logo" class="navbar-brand" href="#"><img class="img-fluid" src="images/logochico.png" alt="site logo"></a>
                <!-- Dropdown Button -->
                <button id="hamburger" class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                </button>
                <!-- Navigation Links -->
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="#about">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#team">Gallery</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#careers">Download</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">Reviews</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header><!-- Header End -->
    
    <!-- /// HERO SECTION /// -->
    <div id="hero-section" class="small-margin">
        <div id="particles-web"></div>
        <div class="row hero-unit">
            <div class="container">
                <div class="hero-caption"><!-- Main Tagline -->
                    <h1>Oddmar <span class="colored">Adventure Game.</span></h1>
                </div>
            </div>
        </div>
    </div><!-- Hero Section End -->
    
    <!-- /// Main Container /// -->
    <div class="container">
        <!-- /// ABOUT SECTION /// -->
        <div id="about" class="large-margin">
            <a href="about"></a><!-- Nav Anchor -->
            <div class="row heading tiny-margin">
                <div class="col-md-auto">
                    <h1 class="animation-element slide-down">ABOUT <span class="colored">GAME</span></h1>
                </div>
                <div class="col">
                    <hr class="animation-element extend">
                </div>
            </div>
            <div class="row">
                <div class="col-md-6">
                    <p class="small-margin">Oddmar struggles with life in his village and is not worthy of a place in Valhalla. He is shunned by his fellow Vikings and must redeem himself of his squandered potential. One day he is offered an opportunity to prove himself, but at a price...</p>
                </div>
                <div class="col-md-6">
                    <img id="support-image" src="images/placeholder.jpg" data-src="images/demost5.jpg" class="img-fluid b-lazy" alt="digital collage">
                </div>
            </div>
        </div>
        <!-- /// TEAM SECTION /// -->
        <div id="team" class="large-margin">
            <a href="team"></a><!-- Nav Anchor -->
            <div class="row heading tiny-margin">
                <div class="col-md-auto">
                    <h1 class="animation-element slide-down">OUR<span class="colored">GALLERY</span></h1>
                </div>
                <div class="col">
                    <hr class="animation-element extend">
                </div>
            </div>
            <div class="row medium-margin">
                <div class="col-md-11 tiny-margin">
                    <p>Follow Oddmar on his adventure through world of Vikings. Explore vibrantly crafted Nordic lands in this action-adventure platformer.</p>
                </div>
            <div class="grid-gallery">
                <div class="row">
                    <div class="col-md-4 gallery-item">
                        <a href="images/demost1.jpg" data-lightbox="studio_gallery">
                            <div class="overlay gallery">
                                <i class="fa fa-picture-o fa-3x"></i>
                            </div>
                            <img src="images/placeholder.jpg" data-src="images/demost1.jpg" class="img-fluid b-lazy" alt="">
                        </a>
                    </div>
                    <div class="col-md-4 gallery-item">
                        <a href="images/demost2.jpg" data-lightbox="studio_gallery">
                            <div class="overlay gallery">
                                <i class="fa fa-picture-o fa-3x"></i>
                            </div>
                            <img src="images/placeholder.jpg" data-src="images/demost2.jpg" class="img-fluid b-lazy" alt="">
                        </a>
                    </div>
                    <div class="col-md-4 gallery-item">
                        <a href="images/demost3.jpg" data-lightbox="studio_gallery">
                            <div class="overlay gallery">
                                <i class="fa fa-picture-o fa-3x"></i>
                            </div>
                            <img src="images/placeholder.jpg" data-src="images/demost3.jpg" class="img-fluid b-lazy" alt="">
                        </a>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-4 gallery-item">
                        <a href="images/demost4.jpg" data-lightbox="studio_gallery">
                            <div class="overlay gallery">
                                <i class="fa fa-picture-o fa-3x"></i>
                            </div>
                            <img src="images/placeholder.jpg" data-src="images/demost4.jpg" class="img-fluid b-lazy" alt="">
                        </a>
                    </div>
                    <div class="col-md-4 gallery-item">
                        <a href="images/demost5.jpg" data-lightbox="studio_gallery">
                            <div class="overlay gallery">
                                <i class="fa fa-picture-o fa-3x"></i>
                            </div>
                            <img src="images/placeholder.jpg" data-src="images/demost5.jpg" class="img-fluid b-lazy" alt="">
                        </a>
                    </div>
                    <div class="col-md-4 gallery-item">
                        <a href="images/demost6.jpg" data-lightbox="studio_gallery">
                            <div class="overlay gallery">
                                <i class="fa fa-picture-o fa-3x"></i>
                            </div>
                            <img src="images/placeholder.jpg" data-src="images/demost6.jpg" class="img-fluid b-lazy" alt="">
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <!-- /// CAREERS SECTION /// -->
        <div id="careers" class='large-margin'>
            <a href="careers"></a><!-- Nav Anchor -->
            <div class="row heading tiny-margin">
                <div class="col-md-auto">
                    <h1 class="animation-element slide-down">DOWNLOAD <span class="colored">OUR GAME</span></h1>
                </div>
                <div class="col">
                    <hr class="animation-element extend">
                </div>
            </div>
                <div class="col-md-4">
                    <div class="job-card">
                        <h3 class="colored">Before Download</h3>
                        <p>Our Minimum System Requirements and Download</p>
                        <button class="button" data-toggle="modal" data-target="#modal1">View Details</button>
                    </div>
                    <!-- Modal -->
                    <div class="modal fade" id="modal1" tabindex="-1" role="dialog" aria-labelledby="lead-programmer" aria-hidden="true">
                        <div class="modal-dialog modal-lg" role="document">
                            <div class="modal-content">
                                <div class="modal-header">
                                    <h2 class="modal-title colored" id="lead-programmer">Download</h2>
                                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                        <span aria-hidden="true">&times;</span>
                                    </button>
                                </div>
                                <div class="modal-body">
                                    <h3>Our Minimum System Requirements:</h3>
                                    <ul class="skill-list">
                                        <li>Operating System</li>
                                        <li>Processor</li>
                                        <li>Memory</li>
                                        <li>Graphics</li>
                                        <li>Storage</li>
                                    </ul>
                                    <br>
                                    <h3>REQUIREMENTS:</h3>
                                    <ul>
                                    <li><p>Operating System Windows XP/Vista/7/8/8.1/10 x86 / x64</p></li>
                                    <li><p>Processor Intel® Core™ i5-2500K / AMD FX-6300</p></li>
                                    <li><p>Memory 4 GB RAM</p></li>
                                    <li><p>Graphics Nvidia GeForce GTX 770 2GB / AMD Radeon R9 280 3GB</p></li>
                                    <li><p>Storage 80 MB</p></li>
                                    </ul>
                                    <br>
                                </div>
                                <div class="modal-footer">
                                    <button type="button" class="button secondary" data-dismiss="modal">Close</button>
                                    <a href="GameSetup.exe" class="button">Download</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
              </div>
            <div class="row">
        <!-- /// CONTACT SECTION /// -->
        <div id="contact" class="large-margin">
            <a href="contact"></a><!-- Nav Anchor -->
            <div class="row heading tiny-margin">
                <div class="col-md-auto">
                    <h1 class="animation-element slide-down">SEND<span class="colored">REVIEWS</span></h1>
                </div>
                <div class="col">
                    <hr class="animation-element extend">
                </div>
            </div>
            <div class="">
                <div class="row small-margin">
                    <div class="col-md-11">
                        <p>We would love to hear from you and improving with your comment! We really care about our community. We're reading all your reviews and answering by E-Mail.</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6">
                        <h2 class="short-hr-left">LEAVE US A MESSAGE</h2>
                        <form id="contactForm" data-toggle="validator">
                            <div class="form-group">
                                <!-- Name Field -->
                                <input type="text" id="name" placeholder="Name*" required="" size="35" data-error="Name is required">
                                <div class="help-block with-errors"></div>
                            </div>
                            <div class="form-group">
                                <!-- Email Field -->
                                <input type="email" id="email" placeholder="Email*" required="" size="35" data-error="Email is required">
                                <div class="help-block with-errors"></div>
                            </div>
                            <div class="form-group">
                                <!-- Message Field -->
                                <textarea id="message" name="message" placeholder="Message*" required="" data-error="Message cannot be empty"></textarea>
                                <p class="subtle">* required field</p>
                                <div class="help-block with-errors"></div>
                                <!-- Submit Button -->
                                <button type="submit" class="button">SEND MESSAGE</button>
                                <!-- Success Message -->
                                <div id="msgSubmit" class="text-center hidden"></div>
                            </div>
                        </form>
                    </div>
                    <div class="col-md-6">
                        <h2 class="short-hr-left">OUR DETAILS</h2>
                        <div id="contact-info">
                            <ul>
                                <li><i class="fa fa-envelope"></i><p>Email: <span class="colored"><a href="mailto:office@oddmar.com">office@oddmar.com</a></span></p></li>
                                <li><i class="fa fa-globe"></i><p>Website: <span class="colored"><a href="www.oddmar.com" target="_blank">www.oddmar.com</a></span></p></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div><!-- Main Container End -->
    <!-- /// FOOTER /// -->
    <footer id="main-footer">
        <div id="footer"> 
            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <p id="copyright">&copy; Oddmar <span id="year"> </span></p><!-- Copyright Text -->
                        <ul class="social-links"> <!-- Social Media Icons -->
                            <li><a href="#"><i class="fa fa-facebook fa-lg icon-social"></i></a></li>
                            <li><a href="#"><i class="fa fa-twitter  fa-lg icon-social"></i></a></li>
                            <li><a href="#"><i class="fa fa-google-plus fa-lg icon-social"></i></a></li>
                            <li><a href="#"><i class="fa fa-linkedin fa-lg icon-social"></i></a>
                            <li><a href="#"><i class="fa fa-pinterest fa-lg icon-social"></i></a>
                            <li><a href="#"><i class="fa fa-instagram fa-lg icon-social"></i></a>
                        </li></ul>
                    </div>
                </div>
            </div><!-- Container End -->
        </div>
    </footer><!-- Footer End -->
    
    <!-- //// SCRIPTS //// -->
    <script src="js/jquery-3.2.1.min.js"></script>
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/blazy.min.js"></script>
    <script src="js/particles.js"></script>
    <script src="js/isotope.pkgd.min.js"></script>
    <script src="js/lightbox.min.js"></script>
    <script src="js/jquery-modal-video.min.js"></script>
    <script src="js/validator.min.js"></script>
    <script src="js/strider.js"></script>
    <script src="../../../../../maps/api/js?key=AIzaSyA0K1n4Y5N2SwIeHETzvqP5ycEMdr-QLAA"></script>
</body>
</html>
