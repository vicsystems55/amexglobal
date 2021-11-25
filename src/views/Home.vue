<template>
  <div class="">
   <div class="preloader">
        <img class="preloader__image" width="60" src="assets/images/resources/logo.png" alt="" />
    </div>
    <!-- /.preloader -->
    <div class="page-wrapper">
        <header class="main-header clearfix">
            <div style="background-color: white;" class="main-header__logo">
                <a href="index.html">
                    <img style="width: 50px; height: 50px;" src="assets/images/resources/logo.png" alt="">
                </a>
            </div>
            <div class="main-menu-wrapper">
                <div class="main-menu-wrapper__top">
                    <div class="main-menu-wrapper__top-inner">
                        <div class="main-menu-wrapper__left">
                            <div class="main-menu-wrapper__left-content">
                                <div class="main-menu-wrapper__left-text">
                                    <p>Welcome to Apex Global Foundation</p>
                                </div>
                                <div class="main-menu-wrapper__left-email-box">
                                    <div class="icon">
                                        <i class="fas fa-envelope"></i>
                                    </div>
                                    <div class="email">
                                        <a href="mailto:needhelp@company.com">support@apexglobalfoundation.com.ng</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="main-menu-wrapper__right">
                            <div class="main-menu-wrapper__right-social">
                                <a href="#"><i class="fab fa-twitter"></i></a>
                                <a href="#"><i class="fab fa-facebook-square"></i></a>
                                
                            </div>
                        </div>
                    </div>
                </div>
                <div class="main-menu-wrapper__bottom">
                    <nav class="main-menu">
                        <div class="main-menu__inner">
                            <a href="#" class="mobile-nav__toggler" @click="showNav()" ><i class="fa fa-bars"></i></a>
                            <ul class="main-menu__list">
                                
                                
                                   <li><a href="">Home</a></li>
                                   <li><a href="/#/about">About</a></li>
                                      <!-- <li><a href="contact.html">Services</a></li> -->
                                <li><a href="/#/contact">Contact</a></li>   
                                
                            </ul>
                            <div class="main-menu__right">
                                <!-- <a href="#" class="main-menu__search search-toggler icon-magnifying-glass"></a> -->
                              
                                <div class="main-menu__phone-contact">
                                    <div class="main-menu__phone-icon">
                                        <span class="icon-chat"></span>
                                    </div>
                                    <div class="main-menu__phone-number">
                                        <p>Call Anytime</p>
                                        <a href="tel:92 666 888 0000">92 666 888 0000</a>
                                    </div>
                                </div>
                                <a href="causes-details.html" class="main-menu__donate-btn"><i class="fa fa-heart"></i>Donate </a>
                            </div>
                        </div>
                    </nav>
                </div>
            </div>

        </header>

        <div class="stricky-header stricked-menu main-menu">
            <div class="sticky-header__content"></div><!-- /.sticky-header__content -->
        </div><!-- /.stricky-header -->


        <section class="main-slider">
            <div class="swiper-container thm-swiper__slider" data-swiper-options='{"slidesPerView": 1, "loop": false,
    "effect": "fade",
     "pagination": {
        "el": "#main-slider-pagination",
        "type": "bullets",
        "clickable": true
      },
    "navigation": {
        "nextEl": "#main-slider__swiper-button-next",
        "prevEl": "#main-slider__swiper-button-prev"
    },
    "autoplay": {
        "delay": 50000
    }}'>
                <div class="swiper-wrapper">
                    <div class="swiper-slide">
                        <div class="image-layer"
                            style="background-image: url(assets/images/backgrounds/slide1.jpg);">
                        </div>
                        <div class="image-layer-overlay"></div>
                        <!-- /.image-layer -->
                        <div class="container">
                            <div class="row">
                                <div class="col-lg-8">
                                    <div class="main-slider__content">
                                        <p>Helping Them Today</p>
                                        <h2>Help the Less Priviledged <br> in Need</h2>
                                        <a href="#" class="thm-btn"><i class="fas fa-arrow-circle-right"></i>Learn
                                            More</a>
                                        <div class="main-slider__shape-1 zoom-fade">
                                            <img src="assets/images/shapes/main-slider-1-shape-1.png" alt="">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- <div class="swiper-slide">
                        <div class="image-layer"
                            style="background-image: url(assets/images/backgrounds/slide2.jpg);">
                        </div>
                        <div class="image-layer-overlay"></div>
                      
                        <div class="container">
                            <div class="row">
                                <div class="col-lg-8">
                                    <div class="main-slider__content">
                                        <p>Helping Them Today</p>
                                        <h2>Help the Less Priviledged <br> in Need</h2>
                                        <a href="#" class="thm-btn"><i class="fas fa-arrow-circle-right"></i>Learn
                                            More</a>
                                        <div class="main-slider__shape-1 zoom-fade">
                                            <img src="assets/images/shapes/main-slider-1-shape-1.png" alt="">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="image-layer"
                            style="background-image: url(assets/images/backgrounds/slide3.jpg);">
                        </div>
                        <div class="image-layer-overlay"></div>
                      
                        <div class="container">
                            <div class="row">
                                <div class="col-lg-8">
                                    <div class="main-slider__content">
                                        <p>Helping Them Today</p>
                                        <h2>Help the Less Priviledged <br> in Need</h2>
                                        <a href="#" class="thm-btn"><i class="fas fa-arrow-circle-right"></i>Learn
                                            More</a>
                                        <div class="main-slider__shape-1 zoom-fade">
                                            <img src="assets/images/shapes/main-slider-1-shape-1.png" alt="">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div> -->
                </div>
                <div class="main-slider__counter">
                    <ul class="main-slider__counter-box list-unstyled">
                        <li>
                            <h5 class="main-sldier__counter-digit">4390</h5>
                            <span class="main-slider__counter-text">Volunteers are Available</span>
                        </li>
                        <li>
                            <h5 class="main-sldier__counter-digit">$8,900</h5>
                            <span class="main-slider__counter-text">Funds Raised by People</span>
                        </li>
                    </ul>
                </div>
                <!-- If we need navigation buttons -->
                <!-- <div class="swiper-pagination" id="main-slider-pagination"></div> -->
                <!-- <div class="main-slider__nav">
                    <div class="swiper-button-prev" id="main-slider__swiper-button-next"><i
                            class="icon-right-arrow icon-left-arrow"></i>
                    </div>
                    <div class="swiper-button-next" id="main-slider__swiper-button-prev"><i
                            class="icon-right-arrow"></i>
                    </div>
                </div> -->
            </div>
        </section>

        <!--Welcome One Start-->
        <section class="welcome-one">
            <div class="container">
                <div class="row">
                    <div class="col-xl-6 col-lg-6">
                        <div class="welcome-one__left">
                            <div class="welcome-one__img-box">
                                <img src="assets/images/resources/inschool.jpg" alt="">
                                <div class="welcome-one__img-box-2">
                                    <img src="assets/images/resources/inschool2.jpg" alt="">
                                </div>
                                <h2 class="welcome-one__bottom-text">Helping Today</h2>
                                <div class="welcome-one__heart-icon">
                                    <img src="assets/images/resources/welcome-one-heart-icon.png" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-6 col-lg-6">
                        <div class="welcome-one__right">
                            <div class="section-title text-left">
                                <span class="section-title__tagline">Welcome to Apex Global Foundation</span>
                                <h2 class="section-title__title">Helping each other can make world better</h2>
                            </div>
                            <p class="welcome-one__right-text">
                                A world of hope, tolerance and social justice, where poverty has been overcome and all people live in dignity and security.
                            </p>
                            <div class="welcome-one__our-mission-and-story">
                                <div class="welcome-one__mission-and-story-single">
                                    <h3><i class="fas fa-arrow-circle-right"></i>Our Mission</h3>
                                    <p class="welcome-one__our-mission-and-story-text">Reach the needy in the society</p>
                                </div>
                                <div class="welcome-one__mission-and-story-single">
                                    <h3><i class="fas fa-arrow-circle-right"></i>Our Vision</h3>
                                    <p class="welcome-one__our-mission-and-story-text">Get</p>
                                </div>
                            </div>
                           
                           
                            <a href="#" class="welcome-one__btn thm-btn"><i class="fas fa-arrow-circle-right"></i>Learn
                                More</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--Welcome One End-->

        <!--Causes One Start-->
    
        <!--Causes One End-->

        <!--Join One Start-->
        <section class="join-one">
            <div class="join-one-bg jarallax" data-jarallax data-speed="0.2" data-imgPosition="50% 0%"
                style="background-image: url(assets/images/backgrounds/join-one-bg.jpg)"></div>
            <div class="container">
                <div class="row">
                    <div class="col-xl-12">
                        <div class="join-one__inner">
                               <h2 class="section-title__title text-white">Find the popular cause <br> and donate them</h2>
                            <a href="#" class="join-one__btn thm-btn"><i class="fas fa-arrow-circle-right"></i>Learn
                                More</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--Join One End-->

        <!--Three Boxes Start-->
        <section class="three-boxes">
            <div class="container-box">
                <div class="row">
                    <div class="col-xl-4">
                        <!--Three Boxes Single-->
                        <div class="three-boxes__single">
                            <div class="three-boxes__single-bg"
                                style="background-image: url(assets/images/resources/three-boxes-img-1.jpg)"></div>
                            <div class="three-boxes__content">
                                <div class="three-boxes__icon">
                                    <span class="icon-fast-food"></span>
                                </div>
                                <div class="three-boxes__text-box">
                                    <h2>Healthy Food</h2>
                                    <p class="three-boxes__text">Lorem ipsum is simply free text available amet,
                                        consectetuer adipiscing elit. There are not many passages of ipsum.</p>
                                    <a href="#" class="three-boxes__btn"><i class="fa fa-heart"></i>Donate </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-4">
                        <!--Three Boxes Single-->
                        <div class="three-boxes__single three-boxes__single-item-two">
                            <div class="three-boxes__single-bg"
                                style="background-image: url(assets/images/resources/three-boxes-img-22.jpg)"></div>
                            <div class="three-boxes__content">
                                <div class="three-boxes__icon">
                                    <span class="icon-water"></span>
                                </div>
                                <div class="three-boxes__text-box">
                                    <h2>Clean Water</h2>
                                    <p class="three-boxes__text">Lorem ipsum is simply free text available amet,
                                        consectetuer adipiscing elit. There are not many passages of ipsum.</p>
                                    <a href="#" class="three-boxes__btn"><i class="fa fa-heart"></i>Donate </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-4">
                        <!--Three Boxes Single-->
                        <div class="three-boxes__single three-boxes__single-item-three">
                            <div class="three-boxes__single-bg"
                                style="background-image: url(assets/images/resources/three-boxes-img-33.jpg)"></div>
                            <div class="three-boxes__content">
                                <div class="three-boxes__icon">
                                    <span class="icon-health-check"></span>
                                </div>
                                <div class="three-boxes__text-box">
                                    <h2>Medical Treatment</h2>
                                    <p class="three-boxes__text">Lorem ipsum is simply free text available amet,
                                        consectetuer adipiscing elit. There are not many passages of ipsum.</p>
                                    <a href="#" class="three-boxes__btn"><i class="fa fa-heart"></i>Donate </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--Three Boxes End-->

        <!--Helping One Start-->
        <section class="contact-page">
            <div class="container">
                <div class="section-title text-center">
                    <span class="section-title__tagline">Contact With Us</span>
                    <h2 class="section-title__title">We love to hear from our <br> happy customers</h2>
                </div>
                <div class="row">
                    <div class="col-xl-6 col-lg-6">
                        <div class="contact-page__left">
                            <div class="contact-page__img">
                                <img src="assets/images/resources/contact-page-img-1.jpg" alt="">
                            </div>
                            
                            <div class="contact-page__contact-info">
                                <ul class="contact-page__contact-list list-unstyled">
                                    <li>
                                        <div class="icon">
                                            <span class="icon-chat"></span>
                                        </div>
                                        <div class="text">
                                            <p>Call Anytime</p>
                                            <a href="tel:92 666 888 0000">92 666 888 0000</a>
                                        </div>
                                    </li>
                                    <li>
                                        <div class="icon">
                                            <span class="icon-message"></span>
                                        </div>
                                        <div class="text">
                                            <p>Send Email</p>
                                            <a href="mailto:support@apexglobalfoundation.com.n">support@apexglobalfoundation.com.ng</a>
                                        </div>
                                    </li>
                                    <li>
                                        <div class="icon">
                                            <span class="icon-address"></span>
                                        </div>
                                        <div class="text">
                                            <p>Visit Office</p>
                                            <h5>Fudie Mall plaza Landmark: Chida hotel beside  Didi building material Plaza number: C2</h5>
                                        </div>
                                    </li>

                                    <li>
                                        <div class="icon">
                                            <span class="icon-address"></span>
                                        </div>
                                        <div class="text">
                                            <p>Visit Office</p>
                                            <h5>Lagos office no 11 Knight Frank building, off campball Street lagos Island</h5>
                                        </div>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-6 col-lg-6">
                        <div class="contact-page__form">
                            <form action="assets/inc/sendemail.php" class="contact-page__main-form contact-form-validated">
                                <div class="row">
                                    <div class="col-xl-12">
                                        <div class="contact-page__input-box">
                                            <input type="text" placeholder="Your name" name="name">
                                        </div>
                                    </div>
                                </div>
                                <div class="row">
                                    <div class="col-xl-6">
                                        <div class="contact-page__input-box">
                                            <input type="email" placeholder="Email address" name="email">
                                        </div>
                                    </div>
                                    <div class="col-xl-6">
                                        <div class="contact-page__input-box">
                                            <input type="text" placeholder="Subject" name="subject">
                                        </div>
                                    </div>
                                </div>
                                <div class="row">
                                    <div class="col-xl-12">
                                        <div class="contact-page__input-box">
                                            <input type="text" placeholder="Phone Number" name="phone">
                                        </div>
                                    </div>
                                    <div class="col-xl-12">
                                        <div class="contact-page__input-box">
                                            <textarea name="message" placeholder="Write message"></textarea>
                                        </div>
                                        <button type="submit" class="thm-btn contact-page__btn"><i class="fas fa-arrow-circle-right"></i>Send a Message</button>
                                    </div>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--Helping One End-->
              <!-- <section class="contact-page-google-map">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4562.753041141002!2d-118.80123790098536!3d34.152323469614075!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80e82469c2162619%3A0xba03efb7998eef6d!2sCostco+Wholesale!5e0!3m2!1sbn!2sbd!4v1562518641290!5m2!1sbn!2sbd" class="contact-page-google-map__one" allowfullscreen></iframe>

        </section> -->

        <!--Gallery One Start-->
        <section class="gallery-one">
            <div class="gallery-one__container-box clearfix">
                <div class="gallery-one__carousel owl-theme owl-carousel">
                    <!--Gallery One Single-->
                    <div class="gallery-one__single">
                        <div class="gallery-one__img-box">
                            <img src="assets/images/gallery/gallery-1-1.jpg" alt="">
                            <div class="gallery-one__hover-content-box">
                                <h2>Child Education</h2>
                                <p>Charity</p>
                            </div>
                        </div>
                    </div>
                    <!--Gallery One Single-->
                    <div class="gallery-one__single">
                        <div class="gallery-one__img-box">
                            <img src="assets/images/gallery/gallery-1-2.jpg" alt="">
                            <div class="gallery-one__hover-content-box">
                                <h2>Child Education</h2>
                                <p>Charity</p>
                            </div>
                        </div>
                    </div>
                    <!--Gallery One Single-->
                    <div class="gallery-one__single">
                        <div class="gallery-one__img-box">
                            <img src="assets/images/gallery/gallery-1-3.jpg" alt="">
                            <div class="gallery-one__hover-content-box">
                                <h2>Child Education</h2>
                                <p>Charity</p>
                            </div>
                        </div>
                    </div>
                    <!--Gallery One Single-->
                    <div class="gallery-one__single">
                        <div class="gallery-one__img-box">
                            <img src="assets/images/gallery/gallery-1-4.jpg" alt="">
                            <div class="gallery-one__hover-content-box">
                                <h2>Child Education</h2>
                                <p>Charity</p>
                            </div>
                        </div>
                    </div>
                    <!--Gallery One Single-->
                    <div class="gallery-one__single">
                        <div class="gallery-one__img-box">
                            <img src="assets/images/gallery/gallery-1-5.jpg" alt="">
                            <div class="gallery-one__hover-content-box">
                                <h2>Child Education</h2>
                                <p>Charity</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--Gallery One End-->

        <!--Testimonial One Start-->
        <!-- <section class="testimonial-one">
            <div class="testimonial-one-bg"
                style="background-image: url(assets/images/backgrounds/testimonial-1-bg.jpg)"></div>
            <div class="container">
                <div class="row">
                    <div class="col-xl-4">
                        <div class="testimonial-one__left">
                            <div class="section-title text-left">
                                <span class="section-title__tagline">Our Testimonials</span>
                                <h2 class="section-title__title">What they’re talking about charity</h2>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-8">
                        <div class="testimonial-one__right">
                            <div class="testimonial-one__carousel owl-theme owl-carousel">
                                
                                <div class="testimonial-one__single">
                                    <p class="testimonial-one__text">Lorem ipsum is simply free text dolor sit amet,
                                        consectetur notted adipisicing elit sed do eiusmod tempor incididunt ut labore
                                        et dolore magna aliqua.</p>
                                    <div class="testimonial-one__client-info">
                                        <div class="testimonial-one__client-img">
                                            <img src="assets/images/testimonial/testimonial-1-img-1.png" alt="">
                                            <div class="testimonial-one__quote">

                                            </div>
                                        </div>
                                        <div class="testimonial-one__client-name">
                                            <h3>Kevin Martin</h3>
                                            <p>Volunteer</p>
                                        </div>
                                    </div>
                                </div>
                               
                                <div class="testimonial-one__single">
                                    <p class="testimonial-one__text">Lorem ipsum is simply free text dolor sit amet,
                                        consectetur notted adipisicing elit sed do eiusmod tempor incididunt ut labore
                                        et dolore magna aliqua.</p>
                                    <div class="testimonial-one__client-info">
                                        <div class="testimonial-one__client-img">
                                            <img src="assets/images/testimonial/testimonial-1-img-2.png" alt="">
                                            <div class="testimonial-one__quote">

                                            </div>
                                        </div>
                                        <div class="testimonial-one__client-name">
                                            <h3>Jessica Brown</h3>
                                            <p>Volunteer</p>
                                        </div>
                                    </div>
                                </div>
                             
                                <div class="testimonial-one__single">
                                    <p class="testimonial-one__text">Lorem ipsum is simply free text dolor sit amet,
                                        consectetur notted adipisicing elit sed do eiusmod tempor incididunt ut labore
                                        et dolore magna aliqua.</p>
                                    <div class="testimonial-one__client-info">
                                        <div class="testimonial-one__client-img">
                                            <img src="assets/images/testimonial/testimonial-1-img-1.png" alt="">
                                            <div class="testimonial-one__quote">

                                            </div>
                                        </div>
                                        <div class="testimonial-one__client-name">
                                            <h3>Jessica Brown</h3>
                                            <p>Volunteer</p>
                                        </div>
                                    </div>
                                </div>
                               
                                <div class="testimonial-one__single">
                                    <p class="testimonial-one__text">Lorem ipsum is simply free text dolor sit amet,
                                        consectetur notted adipisicing elit sed do eiusmod tempor incididunt ut labore
                                        et dolore magna aliqua.</p>
                                    <div class="testimonial-one__client-info">
                                        <div class="testimonial-one__client-img">
                                            <img src="assets/images/testimonial/testimonial-1-img-2.png" alt="">
                                            <div class="testimonial-one__quote">

                                            </div>
                                        </div>
                                        <div class="testimonial-one__client-name">
                                            <h3>Kevin Martin</h3>
                                            <p>Volunteer</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section> -->
        <!--Testimonial One End-->

        <!--Help Them Start-->
  
        <!--Help Them End-->

        <!-- <section class="news-one">
            <div class="container">
                <div class="row">
                    <div class="col-xl-8 col-lg-8">
                        <div class="section-title text-left">
                            <span class="section-title__tagline">Get Daily Updates</span>
                            <h2 class="section-title__title">Latest news & articles directly <br> coming from the blog
                            </h2>
                        </div>
                    </div>
                    <div class="col-xl-4 col-lg-4">
                        <div class="news-one__button-box">
                            <a href="#" class="news-one__btn thm-btn"><i class="fas fa-arrow-circle-right"></i>View
                                More</a>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-xl-6 col-lg-6">
                        <div class="news-one__left">
                            <div class="news-one__img">
                                <img src="assets/images/blog/news-one-img-1.jpg" alt="">
                                <a href="news-details.html">
                                    <i class="fa fa-plus"></i>
                                </a>
                            </div>
                            <div class="news-one__bottom">
                                <ul class="list-unstyled news-one__meta">
                                    <li>20 Jan, 2021</li>
                                    <li><span>/</span></li>
                                    <li><a href="#">2 Comments</a></li>
                                </ul>
                                <h3 class="news-one__title">
                                    <a href="news-details.html">Donation is Hope for Less Priviledged Childrens in Africa</a>
                                </h3>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-6 col-lg-6">
                        <div class="news-one__right">
                            <div class="news-one__right-single">
                                <div class="news-one__right-img">
                                    <img src="assets/images/blog/news-one-right-img-1.jpg" alt="">
                                    <a href="news-details.html">
                                        <i class="fa fa-plus"></i>
                                    </a>
                                </div>
                                <div class="news-one__right-content">
                                    <ul class="list-unstyled news-one__right-meta">
                                        <li>20 Jan, 2021</li>
                                        <li><span>/</span></li>
                                        <li><a href="#">2 Comments</a></li>
                                    </ul>
                                    <h3 class="news-one__right-title">
                                        <a href="news-details.html">How Does Malnutrition Affect Children?</a>
                                    </h3>
                                </div>
                            </div>
                            <div class="news-one__right-single">
                                <div class="news-one__right-img">
                                    <img src="assets/images/blog/news-one-right-img-2.jpg" alt="">
                                    <a href="news-details.html">
                                        <i class="fa fa-plus"></i>
                                    </a>
                                </div>
                                <div class="news-one__right-content">
                                    <ul class="list-unstyled news-one__right-meta">
                                        <li>20 Jan, 2021</li>
                                        <li><span>/</span></li>
                                        <li><a href="#">2 Comments</a></li>
                                    </ul>
                                    <h3 class="news-one__right-title">
                                        <a href="news-details.html">Capitalize on low hanging fruit to identify</a>
                                    </h3>
                                </div>
                            </div>
                            <div class="news-one__right-single">
                                <div class="news-one__right-img">
                                    <img src="assets/images/blog/news-one-right-img-3.jpg" alt="">
                                    <a href="news-details.html">
                                        <i class="fa fa-plus"></i>
                                    </a>
                                </div>
                                <div class="news-one__right-content">
                                    <ul class="list-unstyled news-one__right-meta">
                                        <li>20 Jan, 2021</li>
                                        <li><span>/</span></li>
                                        <li><a href="#">2 Comments</a></li>
                                    </ul>
                                    <h3 class="news-one__right-title">
                                        <a href="news-details.html">Override the digital divide with additional</a>
                                    </h3>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section> -->

        <!--Brand One Start-->
     
        <!--Brand One End-->

        <!--Site Footer One Start-->
        <footer class="site-footer">
            <div class="site-footer-bg" style="background-image: url(assets/images/backgrounds/footer-bg.jpg)"></div>
            <div class="container">
                <div class="site-footer__top">
                    <div class="row">
                        <div class="col-xl-3 col-lg-6 col-md-6 wow fadeInUp" data-wow-delay="100ms">
                            <div class="footer-widget__column footer-widget__about">
                                <h3 class="footer-widget__title">About</h3>
                                <p class="footer-widget__text">Lorem ipsum dolor sit ame consect etur pisicing elit sed
                                    do eiusmod tempor incididunt ut labore.</p>
                                <a href="#" class="footer-widget__about-btn"><i class="fa fa-heart"></i>Donate </a>
                            </div>
                        </div>
                        
                        <div class="col-xl-4 col-lg-6 col-md-6 wow fadeInUp" data-wow-delay="300ms">
                            <div class="footer-widget__column footer-widget__contact">
                                <h3 class="footer-widget__title">Contact</h3>
                                <ul class="list-unstyled footer-widget__contact-list">
                                    <li>
                                        <div class="icon">
                                            <i class="icon-chat"></i>
                                        </div>
                                        <div class="text">
                                            <p>
                                                <span>Call Anytime</span>
                                                <a href="tel:92 666 888 0000">0809 522 4343</a> <br>
                                                <a href="tel:92 666 888 0000">01-8895101</a>
                                                
                                            </p>
                                        </div>
                                    </li>
                                    <li>
                                        <div class="icon">
                                            <i class="icon-message"></i>
                                        </div>
                                        <div class="text">
                                            <p>
                                                <span>Send Email</span>
                                                <a href="mailto:needhelp@company.com">support@apexglobalfoundation.com.ng</a>
                                            </p>
                                        </div>
                                    </li>
                                    <li>
                                        <div class="icon">
                                            <i class="icon-address"></i>
                                        </div>
                                        <div class="text">
                                            <p><span>Visit Office</span>
                                            
                                            Fudie Mall plaza
                                            Landmark: Chida hotel beside  Didi building material
                                            Plaza number: C2
                                            
                                            </p>
                                        </div>
                                    </li>
                                </ul>
                            </div>
                        </div>
                        <div class="col-xl-3 col-lg-6 col-md-6 wow fadeInUp" data-wow-delay="400ms">
                            <div class="footer-widget__column footer-widget__newsletter">
                                <h3 class="footer-widget__title">Newsletter</h3>
                                <p class="footer-widget__newsletter-text">Follow our progress</p>
                                <form class="footer-widget__newsletter-form">
                                    <input type="email" placeholder="Email address" name="email">
                                    <button type="submit" class="footer-widget__newsletter-btn"><i
                                            class="fas fa-arrow-circle-right"></i>Send</button>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="site-footer__bottom">
                    <div class="row">
                        <div class="col-xl-12">
                            <div class="site-footer__bottom-inner">
                                <div class="site-footer__bottom-logo-social">
                                    <div class="site-footer__bottom-logo">
                                        <a href="index.html"><img style="width: 50px; height: 50px;" src="assets/images/resources/logo.jpg"
                                                alt=""></a>
                                    </div>
                                    <div class="site-footer__bottom-social">
                                        <a href="#"><i class="fab fa-twitter"></i></a>
                                        <a href="#"><i class="fab fa-facebook-square"></i></a>
                                     
                                        <a href="#"><i class="fab fa-instagram"></i></a>
                                    </div>
                                </div>
                                <div class="site-footer__bottom-copy-right">
                                    <p>© Copyright 2021 by <a href="#">vicSystems</a></p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </footer>
        <!--Site Footer One End-->


    </div><!-- /.page-wrapper -->


    <div class="" v-bind:class="nav_class">
        <div class="mobile-nav__overlay mobile-nav__toggler" @click="collapseNav()"></div>
        <!-- /.mobile-nav__overlay -->
        <div class="mobile-nav__content">
            <span class="mobile-nav__close mobile-nav__toggler"><i class="fa fa-times"></i></span>

            <div class="logo-box">
                <a href="index.html" aria-label="logo image"><img src="assets/images/resources/logo.png" width="155"
                        alt="" /></a>
            </div>
            <!-- /.logo-box -->
            <div class="mobile-nav__container">
            <ul class="main-menu__list">
            <li><a href="contact.html">Home</a></li>
                           <li><a href="contact.html">About</a></li>
                                <li><a href="contact.html">Contact</a></li>
                            </ul>
            </div>
            <!-- /.mobile-nav__container -->

            <ul class="mobile-nav__contact list-unstyled">
                <li>
                    <i class="fa fa-envelope"></i>
                    <a href="mailto:needhelp@packageName__.com">needhelp@halpes.com</a>
                </li>
                <li>
                    <i class="fa fa-phone-alt"></i>
                    <a href="tel:666-888-0000">666 888 0000</a>
                </li>
            </ul><!-- /.mobile-nav__contact -->
            <div class="mobile-nav__top">
                <div class="mobile-nav__social">
                    <a href="#" class="fab fa-twitter"></a>
                    <a href="#" class="fab fa-facebook-square"></a>
                    <a href="#" class="fab fa-pinterest-p"></a>
                    <a href="#" class="fab fa-instagram"></a>
                </div><!-- /.mobile-nav__social -->
            </div><!-- /.mobile-nav__top -->



        </div>
        <!-- /.mobile-nav__content -->
    </div>
    <!-- /.mobile-nav__wrapper -->

    <div class="search-popup">
        <div class="search-popup__overlay search-toggler"></div>
        <!-- /.search-popup__overlay -->
        <div class="search-popup__content">
            <form action="#">
                <label for="search" class="sr-only">search here</label><!-- /.sr-only -->
                <input type="text" id="search" placeholder="Search Here..." />
                <button type="submit" aria-label="search submit" class="thm-btn">
                    <i class="icon-magnifying-glass"></i>
                </button>
            </form>
        </div>
        <!-- /.search-popup__content -->
    </div>
    <!-- /.search-popup -->

    <a href="#" data-target="html" class="scroll-to-target scroll-to-top"><i class="fa fa-angle-up"></i></a>

  </div>
</template>

<script>
// @ is an alias to /src


export default {

  data() {
    return {
      nav_class: 'mobile-nav__wrapper',
    }
  },
  
  name: 'Home',
  components: {

  },
  methods: {
    showNav(){
      this.nav_class = 'mobile-nav__wrapper expanded'
    },
    collapseNav(){
      this.nav_class = 'mobile-nav__wrapper'
    }
  },
}
</script>
