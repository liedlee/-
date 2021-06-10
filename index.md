<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta http-equiv="X-UA-Compatible" content="ie=edge" />
        <title>Constrata</title>
        <link rel="icon" type="image/png" href="assets/images/favicon.png" />
        <link rel="stylesheet" href="assets/css/bootstrap.min.css" />
        <link rel="stylesheet" href="assets/css/slick.css" />
        <link rel="stylesheet" href="assets/css/slick-theme.css" />
        <link rel="stylesheet" href="assets/css/all.min.css" />
        <link rel="stylesheet" href="assets/css/lightbox.min.css" />
        <link rel="stylesheet" href="assets/css/style.css" />
    </head>
    <body>
        <!-- Start Header -->
        <header>
            <div class="header-area bg-semi py-2">
                <div class="container">
                    <div class="row">
                        <div class="col-md-12">
                            <div class="main-menu">
                                <nav class="navbar navbar-expand-lg aligh-items-center">
                                    <a class="navbar-brand" href="index.html">
                                        <img src="assets/images/logo.png" alt="logo" class="img-fluid" />
                                    </a>
                                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mainMenu" aria-controls="mainMenu" aria-expanded="false" aria-label="Toggle navigation">
                                        <span class="fas fa-bars text-white"></span>
                                    </button>
                                    <div class="collapse navbar-collapse nav-wrapper" id="mainMenu">
                                        <ul class="navbar-nav mx-auto">
                                            <li class="nav-item active dropdown">
                                                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                                    Home
                                                </a>
                                                <ul class="dropdown-menu">
                                                    <li><a class="dropdown-item" href="index.html">Home 1</a></li>
                                                    <li><a class="dropdown-item" href="index-2.html">Home 2</a></li>
                                                    <li><a class="dropdown-item" href="index-3.html">Home 3</a></li>
                                                </ul>
                                            </li>
                                            <li class="nav-item">
                                                <a class="nav-link" href="project_page.html">Projects</a>
                                            </li>
                                            <li class="nav-item">
                                                <a class="nav-link" href="services.html">Services</a>
                                            </li>
                                            <li class="nav-item">
                                                <a class="nav-link" href="about.html">About</a>
                                            </li>
                                            <li class="nav-item">
                                                <a class="nav-link" href="blog.html">Blog</a>
                                            </li>
                                            <li class="nav-item">
                                                <a class="nav-link" href="contact.html">Contact</a>
                                            </li>
                                            <li class="nav-item dropdown">
                                                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                                    Pages
                                                </a>
                                                <ul class="dropdown-menu">
                                                    <li><a class="dropdown-item" href="blog_left_sidebar.html">Blog Left Sedebar</a></li>
                                                    <li><a class="dropdown-item" href="bog_right_sidebar.html">Bog Right Sidebar</a></li>
                                                    <li><a class="dropdown-item" href="blog_details.html">Blog Details</a></li>
                                                    <li><a class="dropdown-item" href="sustainability.html">Sustainability </a></li>
                                                    <li><a class="dropdown-item" href="subcontractor.html">Subcontractor </a></li>
                                                    <li><a class="dropdown-item" href="single_service.html">Single Service </a></li>
                                                    <li><a class="dropdown-item" href="investor.html">Investor</a></li>
                                                    <li><a class="dropdown-item" href="our_team.html">Our Team</a></li>
                                                    <li><a class="dropdown-item" href="project_page_2.html">Project Page 2</a></li>
                                                    <li><a class="dropdown-item" href="project_page_3.html">Project Page 3</a></li>
                                                    <li><a class="dropdown-item" href="project_details.html">Project Details</a></li>
                                                    <li><a class="dropdown-item" href="project_details_2.html">Project Details 2</a></li>
                                                </ul>
                                            </li>
                                        </ul>
                                        <div class="extended-menu">
                                            <ul class="navbar-nav">
                                                <li class="nav-link">
                                                    <a data-bs-toggle="modal" data-bs-target="#searchModal" href="#"><img class="search-icon" src="assets/images/search_icon.png" alt="search" /></a>
                                                </li>
                                                <li class="nav-link">
                                                    <button class="custom-big-btn" data-bs-toggle="modal" data-bs-target="#quoteModal">
                                                        Get A Quote <span><i class="fas fa-caret-right"></i></span>
                                                    </button>
                                                </li>
                                            </ul>
                                        </div>
                                    </div>
                                </nav>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Start Search Modal -->
            <div class="modal fade" id="searchModal" tabindex="-1" aria-hidden="true">
                <div class="modal-dialog modal-fullscreen">
                    <div class="modal-content border-radius-0">
                        <div class="modal-header px-4">
                            <h3 class="heading-3">Search Here</h3>
                            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            <div class="contact-form">
                                <form action="#">
                                    <div class="mb-3">
                                        <input type="search" class="form-control" aria-describedby="searchHelp" placeholder="Search Here" required />
                                        <div id="searchHelp" class="form-text">Type Here Your Text Now.</div>
                                    </div>
                                    <button type="submit" class="custom-btn w-100">Start Searching</button>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- End Search Modal -->
            <!-- Start Quote Modal -->
            <div class="modal fade" id="quoteModal" tabindex="-1" aria-hidden="true">
                <div class="modal-dialog modal-xl">
                    <div class="modal-content border-radius-0">
                        <div class="modal-header px-5">
                            <h3 class="heading-3">Request Your Quote</h3>
                            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body p-4">
                            <div class="contact-form">
                                <form action="#" class="row">
                                    <div class="col-md-6 mb-4">
                                        <div class="form-group">
                                            <label for="user_name">Name</label>
                                            <input type="text" class="form-control" id="user_name" placeholder="Your Full Name" required="" />
                                        </div>
                                    </div>
                                    <div class="col-md-6 mb-4">
                                        <div class="form-group">
                                            <label for="user_email">Email</label>
                                            <input type="email" name="user_email" class="form-control" id="user_email" placeholder="Your Email" required="" />
                                        </div>
                                    </div>
                                    <div class="col-md-6 mb-4">
                                        <div class="form-group">
                                            <label for="user_phone_number">Your Phone</label>
                                            <input type="number" class="form-control" name="user_phone_number" id="user_phone_number" placeholder="Your Phone" required="" />
                                        </div>
                                    </div>
                                    <div class="col-md-6 mb-4">
                                        <div class="form-group">
                                            <label for="user_subject">Subject</label>
                                            <input type="text" class="form-control" name="user_subject" id="user_subject" placeholder="Subject" required="" />
                                        </div>
                                    </div>
                                    <div class="col-md-12">
                                        <div class="form-group">
                                            <label for="user_message">Write Your Message</label>
                                        </div>
                                        <textarea name="user_message" id="user_message" cols="30" rows="10" class="form-control" placeholder="Your Message"></textarea>
                                    </div>
                                    <div class="col-md-12 mt-5">
                                        <button type="submit">Submit Contact</button>
                                    </div>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- End Quote Modal -->
        </header>
        <!-- End Header -->
        <!-- Start Hero Area -->
        <section>
            <div class="hero-area height-700 bg-semi" style="background-image: url(assets/images/hero_area.jpg);">
                <div class="container">
                    <div class="row aligh-items-center">
                        <div class="col-md-12">
                            <div class="hero-text">
                                <h2 class="big-heading text-white">Constrata <span class="light-comma"></span></h2>
                                <p class="sub-title text-white">We’re the the best of architects and engineering creative, passionate and with us let think out of the box.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- End Hero Area -->
        <!-- Start Features Area -->
        <section class="section-ptb">
            <div class="features-area">
                <div class="container">
                    <div class="row align-items-center">
                        <div class="col-lg-6 mb-5 mb-lg-0">
                            <div class="feature-text">
                                <h2 class="heading-2 mb-4">Constrata Efforts to Build Better <span class="light-comma"></span></h2>
                                <h3 class="sub-title-2">We are Market Leader in this City Construction Build company</h3>
                                <div class="text-wrapper py-lg-4 pe-lg-4 pt-3 pt-lg-0">
                                    <p>
                                        Construction is the process of constructing a building or infra structure. Construction differs from manufacturing in mass of similar items without a typically takes place on location for a known
                                        client. Construction as an industry comprises six to nine percent of the gross domestic product of developed countries planning design, and financing; it continues until the project built and ready
                                        for use construction.
                                    </p>
                                </div>
                                <a href="about.html" class="read-more-btn">
                                    Read More <span class="ml-3"><i class="fas fa-caret-right"></i></span>
                                </a>
                            </div>
                        </div>
                        <div class="col-lg-6">
                            <div class="feature-image">
                                <img src="assets/images/building.jpg" alt="building" class="img-fluid w-100" />
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- End Features Area -->
        <!-- Start Services Area -->
        <section class="bg-semi-white section-ptb">
            <div class="services-area-2">
                <div class="container">
                    <div class="row inner-pb">
                        <div class="col-md-12">
                            <div class="section-title">
                                <h2 class="heading-2">Our Services <span class="light-comma"></span></h2>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-4 col-md-6 mb-5 mb-lg-0">
                            <div class="single-service">
                                <div class="icon-container mb-4">
                                    <img src="assets/images/rulers_icon.png" alt="rulers" class="img-fluid" />
                                </div>
                                <div class="service-info">
                                    <h3 class="heading-3">Design And Build</h3>
                                    <p class="my-4">We aim to eliminate the task of dividing your project between different architecture and construction company we are a company that offers design and build.</p>
                                    <a href="single_service.html" class="read-more-btn">Read More</a>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-6 mb-5 mb-lg-0">
                            <div class="single-service">
                                <div class="icon-container mb-4">
                                    <img src="assets/images/brick_icon.png" alt="rulers" class="img-fluid" />
                                </div>
                                <div class="service-info">
                                    <h3 class="heading-3">Design And Build</h3>
                                    <p class="my-4">We aim to eliminate the task of dividing your project between different architecture and construction company we are a company that offers design and build.</p>
                                    <a href="single_service.html" class="read-more-btn">Read More</a>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-6">
                            <div class="single-service">
                                <div class="icon-container mb-4">
                                    <img src="assets/images/loader_icon_01.png" alt="rulers" class="img-fluid" />
                                </div>
                                <div class="service-info">
                                    <h3 class="heading-3">Design And Build</h3>
                                    <p class="my-4">We aim to eliminate the task of dividing your project between different architecture and construction company we are a company that offers design and build.</p>
                                    <a href="single_service.html" class="read-more-btn">Read More</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- End Services Area -->
        <!-- Start Latest Projects -->
        <section class="section-ptb">
            <div class="projects-area">
                <div class="container inner-pb">
                    <div class="row align-items-center">
                        <div class="col-md-5 mb-xs-4">
                            <h2 class="heading-2">Latest Project <span class="light-comma"></span></h2>
                        </div>
                        <div class="col-md-7">
                            <ul class="nav nav-tabs" id="myTab" role="tablist">
                                <li class="nav-item" role="presentation">
                                    <a class="nav-link active" id="all-portfolio-tab" data-bs-toggle="tab" href="#all_portfolio" role="tab">All</a>
                                </li>
                                <li class="nav-item" role="presentation">
                                    <a class="nav-link" id="housing-tab" data-bs-toggle="tab" href="#housing_portfolio" role="tab">House</a>
                                </li>
                                <li class="nav-item" role="presentation">
                                    <a class="nav-link" id="building-tab" data-bs-toggle="tab" href="#building_portfolio" role="tab">Building</a>
                                </li>
                                <li class="nav-item" role="presentation">
                                    <a class="nav-link" id="garden-tab" data-bs-toggle="tab" href="#garden_portfolio" role="tab">Garden</a>
                                </li>
                                <li class="nav-item" role="presentation">
                                    <a class="nav-link" id="office-tab" data-bs-toggle="tab" href="#office_portfolio" role="tab">Office</a>
                                </li>
                                <li class="nav-item" role="presentation">
                                    <a class="nav-link" id="interior-tab" data-bs-toggle="tab" href="#interior_portfolio" role="tab">Interior</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="container-fluid">
                    <div class="portfolios-content">
                        <div class="tab-content">
                            <div class="tab-pane fade show active" id="all_portfolio" role="tabpanel">
                                <div class="row portfolio-wrapper align-items-center">
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_01.jpg" data-lightbox="image-1" data-title="portfolio 01">
                                                <img src="assets/images/project_01.jpg" class="img-fluid w-100" alt="portfolio 01" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_01.jpg" data-lightbox="image-2" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_02.jpg" data-lightbox="image-3" data-title="portfolio 02">
                                                <img src="assets/images/project_02.jpg" class="img-fluid" alt="portfolio 02" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_02.jpg" data-lightbox="image-4" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_03.jpg" data-lightbox="image-5" data-title="portfolio 01">
                                                <img src="assets/images/project_03.jpg" class="img-fluid" alt="portfolio 03" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_03.jpg" data-lightbox="image-6" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_04.jpg" data-lightbox="image-7" data-title="portfolio 05">
                                                <img src="assets/images/project_04.jpg" class="img-fluid" alt="portfolio 04" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_04.jpg" data-lightbox="image-8" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_05.jpg" data-lightbox="image-9" data-title="portfolio 05">
                                                <img src="assets/images/project_05.jpg" class="img-fluid" alt="portfolio 05" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_05.jpg" data-lightbox="image-10" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_06.jpg" data-lightbox="image-11" data-title="portfolio 05">
                                                <img src="assets/images/project_06.jpg" class="img-fluid" alt="portfolio 06" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_06.jpg" data-lightbox="image-12" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="housing_portfolio" role="tabpanel">
                                <div class="row portfolio-wrapper align-items-center">
                                	<div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_02.jpg" data-lightbox="image-3" data-title="portfolio 02">
                                                <img src="assets/images/project_02.jpg" class="img-fluid" alt="portfolio 02" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_02.jpg" data-lightbox="image-4" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_05.jpg" data-lightbox="image-9" data-title="portfolio 05">
                                                <img src="assets/images/project_05.jpg" class="img-fluid" alt="portfolio 05" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_05.jpg" data-lightbox="image-10" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_01.jpg" data-lightbox="image-1" data-title="portfolio 01">
                                                <img src="assets/images/project_01.jpg" class="img-fluid w-100" alt="portfolio 01" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_01.jpg" data-lightbox="image-2" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>

                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_03.jpg" data-lightbox="image-5" data-title="portfolio 01">
                                                <img src="assets/images/project_03.jpg" class="img-fluid" alt="portfolio 03" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_03.jpg" data-lightbox="image-6" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_04.jpg" data-lightbox="image-7" data-title="portfolio 05">
                                                <img src="assets/images/project_04.jpg" class="img-fluid" alt="portfolio 04" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_04.jpg" data-lightbox="image-8" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>

                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_06.jpg" data-lightbox="image-11" data-title="portfolio 05">
                                                <img src="assets/images/project_06.jpg" class="img-fluid" alt="portfolio 06" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_06.jpg" data-lightbox="image-12" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="building_portfolio" role="tabpanel">
                                <div class="row portfolio-wrapper align-items-center">
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_01.jpg" data-lightbox="image-1" data-title="portfolio 01">
                                                <img src="assets/images/project_01.jpg" class="img-fluid w-100" alt="portfolio 01" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_01.jpg" data-lightbox="image-2" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_02.jpg" data-lightbox="image-3" data-title="portfolio 02">
                                                <img src="assets/images/project_02.jpg" class="img-fluid" alt="portfolio 02" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_02.jpg" data-lightbox="image-4" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_03.jpg" data-lightbox="image-5" data-title="portfolio 01">
                                                <img src="assets/images/project_03.jpg" class="img-fluid" alt="portfolio 03" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_03.jpg" data-lightbox="image-6" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_04.jpg" data-lightbox="image-7" data-title="portfolio 05">
                                                <img src="assets/images/project_04.jpg" class="img-fluid" alt="portfolio 04" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_04.jpg" data-lightbox="image-8" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_05.jpg" data-lightbox="image-9" data-title="portfolio 05">
                                                <img src="assets/images/project_05.jpg" class="img-fluid" alt="portfolio 05" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_05.jpg" data-lightbox="image-10" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_06.jpg" data-lightbox="image-11" data-title="portfolio 05">
                                                <img src="assets/images/project_06.jpg" class="img-fluid" alt="portfolio 06" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_06.jpg" data-lightbox="image-12" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="garden_portfolio" role="tabpanel">
                                <div class="row portfolio-wrapper align-items-center">

                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_02.jpg" data-lightbox="image-3" data-title="portfolio 02">
                                                <img src="assets/images/project_02.jpg" class="img-fluid" alt="portfolio 02" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_02.jpg" data-lightbox="image-4" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_03.jpg" data-lightbox="image-5" data-title="portfolio 01">
                                                <img src="assets/images/project_03.jpg" class="img-fluid" alt="portfolio 03" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_03.jpg" data-lightbox="image-6" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_01.jpg" data-lightbox="image-1" data-title="portfolio 01">
                                                <img src="assets/images/project_01.jpg" class="img-fluid w-100" alt="portfolio 01" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_01.jpg" data-lightbox="image-2" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_04.jpg" data-lightbox="image-7" data-title="portfolio 05">
                                                <img src="assets/images/project_04.jpg" class="img-fluid" alt="portfolio 04" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_04.jpg" data-lightbox="image-8" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_05.jpg" data-lightbox="image-9" data-title="portfolio 05">
                                                <img src="assets/images/project_05.jpg" class="img-fluid" alt="portfolio 05" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_05.jpg" data-lightbox="image-10" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_06.jpg" data-lightbox="image-11" data-title="portfolio 05">
                                                <img src="assets/images/project_06.jpg" class="img-fluid" alt="portfolio 06" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_06.jpg" data-lightbox="image-12" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="office_portfolio" role="tabpanel">
                                <div class="row portfolio-wrapper align-items-center">
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_01.jpg" data-lightbox="image-1" data-title="portfolio 01">
                                                <img src="assets/images/project_01.jpg" class="img-fluid w-100" alt="portfolio 01" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_01.jpg" data-lightbox="image-2" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                        <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_03.jpg" data-lightbox="image-5" data-title="portfolio 01">
                                                <img src="assets/images/project_03.jpg" class="img-fluid" alt="portfolio 03" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_03.jpg" data-lightbox="image-6" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_02.jpg" data-lightbox="image-3" data-title="portfolio 02">
                                                <img src="assets/images/project_02.jpg" class="img-fluid" alt="portfolio 02" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_02.jpg" data-lightbox="image-4" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>

                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_04.jpg" data-lightbox="image-7" data-title="portfolio 05">
                                                <img src="assets/images/project_04.jpg" class="img-fluid" alt="portfolio 04" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_04.jpg" data-lightbox="image-8" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_05.jpg" data-lightbox="image-9" data-title="portfolio 05">
                                                <img src="assets/images/project_05.jpg" class="img-fluid" alt="portfolio 05" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_05.jpg" data-lightbox="image-10" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_06.jpg" data-lightbox="image-11" data-title="portfolio 05">
                                                <img src="assets/images/project_06.jpg" class="img-fluid" alt="portfolio 06" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_06.jpg" data-lightbox="image-12" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="tab-pane fade" id="interior_portfolio" role="tabpanel">
                                <div class="row portfolio-wrapper align-items-center">

                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_02.jpg" data-lightbox="image-3" data-title="portfolio 02">
                                                <img src="assets/images/project_02.jpg" class="img-fluid" alt="portfolio 02" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_02.jpg" data-lightbox="image-4" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_03.jpg" data-lightbox="image-5" data-title="portfolio 01">
                                                <img src="assets/images/project_03.jpg" class="img-fluid" alt="portfolio 03" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_03.jpg" data-lightbox="image-6" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                                                        <div class="col-md-4 col-sm-6 ps-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_01.jpg" data-lightbox="image-1" data-title="portfolio 01">
                                                <img src="assets/images/project_01.jpg" class="img-fluid w-100" alt="portfolio 01" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_01.jpg" data-lightbox="image-2" data-title="portfolio 01">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_04.jpg" data-lightbox="image-7" data-title="portfolio 05">
                                                <img src="assets/images/project_04.jpg" class="img-fluid" alt="portfolio 04" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_04.jpg" data-lightbox="image-8" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_05.jpg" data-lightbox="image-9" data-title="portfolio 05">
                                                <img src="assets/images/project_05.jpg" class="img-fluid" alt="portfolio 05" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_05.jpg" data-lightbox="image-10" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-4 col-sm-6 ps-md-0 mb-md-0 mb-3">
                                        <div class="single-portfolio">
                                            <a href="assets/images/project_06.jpg" data-lightbox="image-11" data-title="portfolio 05">
                                                <img src="assets/images/project_06.jpg" class="img-fluid" alt="portfolio 06" />
                                            </a>
                                            <div class="hover-text">
                                                <h2>Construction Build</h2>
                                                <p>CONSTRUCTION SITE</p>
                                            </div>
                                            <div class="plus-btn">
                                                <a href="assets/images/project_06.jpg" data-lightbox="image-12" data-title="portfolio 05">
                                                    <img src="assets/images/plus_icon.png" alt="plus icon" />
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- End Latest Projects -->
        <!-- Start Testimonials Area -->
        <section>
            <div class="testimonials-area" style="background-image: url(assets/images/testimonial_bg.png);">
                <div class="container">
                    <div class="row mb-4">
                        <div class="col-md-12">
                            <div class="section-title">
                                <h2 class="heading-2">What Clients Say <span class="light-comma"></span></h2>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-md-12">
                            <div class="testimonial-slider slider-one">
                                <div class="testimonial-item">
                                    <div class="item-wrapper d-lg-flex align-items-center">
                                        <div class="testimonial-quote col-lg-7 pl-0">
                                            <p>I was lookıng for a desıgn and buıld contractor who knew the job as ı am too busy to run a loft and extensıon project… but needed the space my frıends and neıghbours.</p>
                                            <div class="quote-bio">
                                                <p><b>Abdullah Sajol,</b> SEO , SK 10 Star Villa.</p>
                                            </div>
                                        </div>
                                        <div class="testimonial-img col-lg-5">
                                            <div class="author-img">
                                                <img class="img-fluid" src="assets/images/author.png" alt="author" />
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="testimonial-item">
                                    <div class="item-wrapper d-lg-flex align-items-center">
                                        <div class="testimonial-quote col-lg-7 pl-0">
                                            <p>I was lookıng for a desıgn and buıld contractor who knew the job as ı am too busy to run a loft and extensıon project… but needed the space my frıends and neıghbours.</p>
                                            <div class="quote-bio">
                                                <p><b>Abdullah Sajol,</b> SEO , SK 10 Star Villa.</p>
                                            </div>
                                        </div>
                                        <div class="testimonial-img col-lg-5">
                                            <div class="author-img">
                                                <img class="img-fluid" src="assets/images/author.png" alt="author" />
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="testimonial-item">
                                    <div class="item-wrapper d-lg-flex align-items-center">
                                        <div class="testimonial-quote col-lg-7 pl-0">
                                            <p>I was lookıng for a desıgn and buıld contractor who knew the job as ı am too busy to run a loft and extensıon project… but needed the space my frıends and neıghbours.</p>
                                            <div class="quote-bio">
                                                <p><b>Abdullah Sajol,</b> SEO , SK 10 Star Villa.</p>
                                            </div>
                                        </div>
                                        <div class="testimonial-img col-lg-5">
                                            <div class="author-img">
                                                <img class="img-fluid" src="assets/images/author.png" alt="author" />
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="testimonial-item">
                                    <div class="item-wrapper d-lg-flex align-items-center">
                                        <div class="testimonial-quote col-lg-7 pl-0">
                                            <p>I was lookıng for a desıgn and buıld contractor who knew the job as ı am too busy to run a loft and extensıon project… but needed the space my frıends and neıghbours.</p>
                                            <div class="quote-bio">
                                                <p><b>Abdullah Sajol,</b> SEO , SK 10 Star Villa.</p>
                                            </div>
                                        </div>
                                        <div class="testimonial-img col-lg-5">
                                            <div class="author-img">
                                                <img class="img-fluid" src="assets/images/author.png" alt="author" />
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="testimonial-item">
                                    <div class="item-wrapper d-lg-flex align-items-center">
                                        <div class="testimonial-quote col-lg-7 pl-0">
                                            <p>I was lookıng for a desıgn and buıld contractor who knew the job as ı am too busy to run a loft and extensıon project… but needed the space my frıends and neıghbours.</p>
                                            <div class="quote-bio">
                                                <p><b>Abdullah Sajol,</b> SEO , SK 10 Star Villa.</p>
                                            </div>
                                        </div>
                                        <div class="testimonial-img col-lg-5">
                                            <div class="author-img">
                                                <img class="img-fluid" src="assets/images/author.png" alt="author" />
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- End Testimonials Area -->
        <!-- Start Blogs Area -->
        <section class="section-ptb">
            <div class="blogs-area">
                <div class="container">
                    <div class="row inner-pb">
                        <div class="col-md-12">
                            <div class="section-title">
                                <h2 class="heading-2">Recent News <span class="light-comma"></span></h2>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-4 col-md-6 mb-5 mb-lg-0">
                            <div class="single-blog">
                                <div class="blog-thumb">
                                    <a href="blog_details.html">
                                    	<img src="assets/images/blog_01.jpg" alt="blog 01" class="img-fluid w-100" />
                                    </a>
                                </div>
                                <div class="blog-info py-4">
                                    <h4 class="heading-4">
                                    	<a href="blog_details.html">Black Mold How Dangerous is it and why should you </a>
                                    </h4>
                                </div>
                                <div class="blog-meta d-flex">
                                    <div class="author-info">
                                        <a href="#"><img src="assets/images/author_01.png" alt="author" class="img-fluid me-2" /></a>
                                        <p class="d-inline-block mb-0"><a href="#">Robin Veno</a></p>
                                    </div>
                                    <div class="post-date ms-2">
                                        <p>
                                            <span class="me-2"><i class="far fa-clock"></i></span>15 Feb 2020
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-6 mb-5 mb-lg-0">
                            <div class="single-blog">
                                <div class="blog-thumb">
                                    <a href="blog_details.html">
                                    	<img src="assets/images/blog_02.jpg" alt="blog 01" class="img-fluid w-100" />
                                    </a>
                                </div>
                                <div class="blog-info py-4">
                                    <h4 class="heading-4"><a href="blog_details.html">Water Leaking Between the Gutters and the </a></h4>
                                </div>
                                <div class="blog-meta d-flex">
                                    <div class="author-info">
                                        <a href="#"><img src="assets/images/author_02.png" alt="author" class="img-fluid me-2" /></a>
                                        <p class="d-inline-block mb-0"><a href="#">Jhony Vino</a></p>
                                    </div>
                                    <div class="post-date ms-2">
                                        <p>
                                            <span class="me-2"><i class="far fa-clock"></i></span>22 May 2020
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-6 mb-lg-0">
                            <div class="single-blog">
                                <div class="blog-thumb">
                                    <a href="blog_details.html"><img src="assets/images/blog_03.jpg" alt="blog 01" class="img-fluid w-100" /></a>
                                </div>
                                <div class="blog-info py-4">
                                    <h4 class="heading-4"><a href="blog_details.html">Red Mold in the Bathroom or Shower what is it how? </a></h4>
                                </div>
                                <div class="blog-meta d-flex">
                                    <div class="author-info">
                                        <a href="#"><img src="assets/images/author_03.png" alt="author" class="img-fluid me-2" /></a>
                                        <p class="d-inline-block mb-0"><a href="#">Kaesar Doe</a></p>
                                    </div>
                                    <div class="post-date ms-2">
                                        <p>
                                            <span class="me-2"><i class="far fa-clock"></i></span>26 Apr 2020
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- End Blogs Area -->
        <!-- Start Two Columns Area -->
        <section class="bg-semi-white black-overlay">
            <div class="two-columns-area" style="background-image: url(assets/images/curve_bg.png);">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-6">
                            <div class="two-columns-content py-5">
                                <h2 class="special-heading mb-3">If you Find a High Quality <span>Constrata</span> For your Project?</h2>
                                <p class="mb-4">Constrata will help you get things done with pride.</p>

                                <button class="custom-big-btn" data-bs-toggle="modal" data-bs-target="#quoteModal">
                                 Get A Quote <span><i class="fas fa-caret-right"></i></span>
                               </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- End Two Columns Area -->
        <!-- Start Footer -->
        <footer class="semi-hover-4">
            <div class="footer-area">
                <div class="container-fluid">
                    <div class="row">
                        <div class="col-lg-4 col-md-12 semi-hover-5 ptb-100 text-center">
                            <div class="footer-big-widget">
                                <a href="#"><img src="assets/images/logo.png" alt="logo" class="img-fluid" /></a>
                                <div class="contact-number py-5">
                                    <span>CALL US TODAY</span>
                                    <h2><a href="tel:+185-671-1338">+185-671-1338</a></h2>
                                </div>
                                <div class="social-profiles">
                                    <ul>
                                        <li>
                                            <a href="#"><i class="fab fa-facebook-f"></i></a>
                                        </li>
                                        <li>
                                            <a href="#"><i class="fab fa-twitter"></i></a>
                                        </li>
                                        <li>
                                            <a href="#"><i class="fab fa-linkedin-in"></i></a>
                                        </li>
                                        <li>
                                            <a href="#"><i class="fab fa-instagram"></i></a>
                                        </li>
                                    </ul>
                                </div>
                                <div class="copyright-text mt-5">
                                    <p>Copyright &copy; 2021.Company name All rights reserved.<a target="_blank" href="https://sc.chinaz.com/moban/">&#x7F51;&#x9875;&#x6A21;&#x677F;</a></p>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-8 col-md-12 ptb-100">
                            <div class="row">
                                <div class="col-md-4 ps-xl-4 mb-5 mb-md-0">
                                    <div class="footer-widget">
                                        <h2 class="widget-title">Recent Posts</h2>
                                        <ul class="widget-menu with-icon mt-4">
                                            <li>
                                                <span><i class="fas fa-caret-right"></i></span> <a href="#">Water leakin and the house’s fasci what do i do.</a>
                                            </li>
                                            <li>
                                                <span><i class="fas fa-caret-right"></i></span><a href="#">Red mold in the what is its how and how to get rid.</a>
                                            </li>
                                            <li>
                                                <span><i class="fas fa-caret-right"></i></span><a href="#">Black mold how dangerous is it and zshoul you remove it.</a>
                                            </li>
                                            <li>
                                                <span><i class="fas fa-caret-right"></i></span><a href="#">White mold how is it and zshoul you remove it.</a>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                                <div class="col-md-4 mb-5 mb-md-0">
                                    <div class="footer-widget">
                                        <h2 class="widget-title">Company</h2>
                                        <ul class="widget-menu mt-4">
                                            <li><a href="#">Home</a></li>
                                            <li><a href="#">Company News</a></li>
                                            <li><a href="#">Project</a></li>
                                            <li><a href="#">Who We Are</a></li>
                                            <li><a href="#">Our Services</a></li>
                                            <li><a href="#">Project</a></li>
                                            <li><a href="#">Contact Us</a></li>
                                        </ul>
                                    </div>
                                </div>
                                <div class="col-md-4">
                                    <div class="footer-widget">
                                        <h2 class="widget-title">About Us</h2>
                                        <ul class="widget-menu mt-4">
                                            <li><a href="#">Our Company</a></li>
                                            <li><a href="#">Contact Us</a></li>
                                            <li><a href="#">Our Services</a></li>
                                            <li><a href="#">Projects</a></li>
                                            <li><a href="#">Career</a></li>
                                            <li><a href="#">Our Team</a></li>
                                            <li><a href="#">Price & Plans</a></li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </footer>
        <!-- End Footer -->
        <script src="assets/js/jquery-3.5.1.min.js"></script>
        <script src="assets/js/bootstrap.bundle.min.js"></script>
        <script src="assets/js/slick.min.js"></script>
        <script src="assets/js/lightbox.min.js"></script>
        <script src="assets/js/main.js"></script>
    </body>
</html>
