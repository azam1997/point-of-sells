# point-of-sells
ssms
<!DOCTYPE html>
<html dir="ltr" lang="en-US">


<meta http-equiv="content-type" content="text/html;charset=UTF-8" />
<head>
    <!-- Metas -->
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="LionCoders" />
    <!-- Links -->
    <link rel="icon" type="image/png" href="#" />
    <!-- google fonts-->
       <link href="https://fonts.googleapis.com/css?family=Poppins:300,400,500,600,700" rel="stylesheet">
    <link href="http://fonts.googleapis.com/css?family=Playfair+Display:300,400,500,600,700" rel="stylesheet" type="text/css" media="all" />
    <!-- Plugins CSS -->
    <link href="css/plugins.css" rel="stylesheet" />
    <!-- style CSS -->
    <link href="css/style.css" rel="stylesheet" />
    <!-- Document Title -->
    <title>Minimal ecommerce HTML Template</title>
</head>

<body>
  <!--Header Area starts-->
  <div id="header" class="header-menu v1">
    <div class="container-fluid pad-lr-30">
      <div class="row align-items-center">
        <div class="col-md-3">
          <div class="logo">
            <a href="#">
              <img src="images/logo-black.png" alt="Brand logo">
            </a>
          </div>
        </div>
        <div class="col-md-6 d-none-1">
          <div class="main-header-inner">
            <div class="main-menu v1">
              <nav id="mobile-menu">
                <ul>
                  <li class="active"><a href="index.html">Home</a></li>
                  <li class=""><a href="shop.html">Shop</a>
                    <ul class="dropdown dropdown-icon">
                      <li><a href="product-details.html">Product Details</a></li>
                    </ul>
                  </li>
                  <li><a href="about.html">About us</a></li>                  
                  <li><a href="blog.html">Blog</a>
                    <ul class="dropdown dropdown-icon">
                      <li><a href="blog-single.html">Blog Post</a></li>                      
                    </ul>
                  </li>
                  <li><a href="contact.html">Contact</a></li>
                </ul>
              </nav>
            </div>
          </div>
        </div>
        <div class="col-md-3 text-right d-none-1">
          <ul class="offset-menu-wrapper">
            <li>
              <a id="searchBtn" class="search-btn"><i class="ti-search"></i></a>
              <div class="search-container">
                <div id="search" class="">
                  <button type="button" class="close"><span class="ti-close"></span></button>
                  <form class="middle-v">
                    <ul class="search-menu text-center mar-bot-30">
                      <li><a href="#">All Categories</a></li>
                      <li><a href="#">Men</a></li>
                      <li><a href="#">Women</a></li>
                      <li><a href="#">Kids</a></li>
                    </ul>
                    <input id="search_element" type="search" placeholder="Type &amp; hit enter">
                  </form>
                </div>
              </div>
            </li>
            <li class="user-menu">
              <i class="ti-user"></i>
              <ul class="user-dropdown-menu">
                <li><a href="my-account.html">My Account</a></li>
                <li><a href="wishlist.html">Wishlist</a></li>
                <li><a href="shop-checkout.html">Checkout</a></li>
                <li><a href="shop-cart.html">Shopcart</a></li>
                <li><a href="order-tracking.html">Order Tracking</a></li>
                <li><a href="login.html">Login</a></li>
              </ul>
            </li>
            <li class="cart__menu">
              <i class="ti-shopping-cart"></i>
              <span>3</span>
            </li>
          </ul>
        </div>
        <div class="col-12 d-block">
          <div class="mobile-menu">
            <ul class="res-cart offset-menu-wrapper d-none-3">
              <li class="cart__menu">
                <i class="ti-shopping-cart"></i>
                <span>3</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="body__overlay"></div>
  <!-- Offset Wrapper starts-->
  <div class="offset__wrapper">
    <div class="shopping__cart">
      <div class="shopping__cart__inner">
        <div class="offsetmenu__close__btn">
          <i class="ion-android-close"></i>
        </div>
        <div class="shp__cart__wrap">
          <div class="shp__single__product">
            <div class="shp__pro__thumb">
              <a href="#">
                <img src="images/promo/cart-1-300x350.jpg" alt="product images">
              </a>
            </div>
            <div class="shp__pro__details">
              <h2><a href="product-details.html">North Star Blazer</a></h2>
              <span>QTY: 1</span>
              <span class="shp__price">$105.00</span>
            </div>
            <div class="remove__btn">
              <a href="#" title="Remove this item"><i class="ion-android-close"></i></a>
            </div>
          </div>
          <div class="shp__single__product">
            <div class="shp__pro__thumb">
              <a href="#">
                <img src="images/promo/cart-2-300x350.jpg" alt="product images">
              </a>
            </div>
            <div class="shp__pro__details">
              <h2><a href="product-details.html">Thermoball Full zip jacket</a></h2>
              <span>QTY: 1</span>
              <span class="shp__price">$25.00</span>
            </div>
            <div class="remove__btn">
              <a href="#" title="Remove this item"><i class="ion-android-close"></i></a>
            </div>
          </div>
        </div>
        <ul class="shoping__total">
          <li class="subtotal">Subtotal:</li>
          <li class="total__price">$130.00</li>
        </ul>
        <ul class="shopping__btn">
          <li><a href="shop-cart.html">View Cart</a></li>
          <li class="shp__checkout"><a href="shop-checkout.html">Checkout</a></li>
        </ul>
      </div>
    </div>
  </div>
  <!-- Offset Wrapper ends -->
  <!-- Header Area  ends -->
  
    <!--Breadcrumb Area start-->
    <div class="breadcrumb-section bg-s" style="background-image: url(images/breadcrumb/breadcrumb-5.jpg)">
        <div class="container-fluid ">
            <div class="row">
                <div class="breadcrumb-content middle-v t-center">
                    <h3 class="page-title">Login </h3>
                    <ul>
                        <li class="active"><a href="#">Home</a></li>
                        <li><a href="login.html">Login</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <!--Breadcrumb Area ends-->
    <!--User login section starts-->
    <section class="user-login-section">
        <div class="container">
            <div class="row">
                <div class="col-md-6 offset-md-3 tabs style1 text-center">
                    <ul class="ui-list nav nav-tabs justify-content-center mar-tb-30" role="tablist">
                        <li class="nav-item">
                            <a class="nav-link active" data-toggle="tab" href="#login" role="tab" aria-selected="true">Login</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" data-toggle="tab" href="#register" role="tab" aria-selected="false">Register</a>
                        </li>
                    </ul>
                </div>
                <div class="col-md-6 offset-md-3">
                    <div class="ui-dash tab-content mar-bot-30">
                        <div class="tab-pane fade show active" id="login" role="tabpanel">
                            <form id="login-form" action="#" method="post">
                                <div class="form-group">
                                    <input type="text" name="username" id="username" tabindex="1" class="form-control" placeholder="email" value="" required>
                                </div>
                                <div class="form-group">
                                    <input type="password" name="password" id="password" tabindex="2" class="form-control" placeholder="Password">
                                </div>
                                <div class="row">
                                    <div class="col-md-6 col-6 text-left">
                                        <div class="res-box">
                                            <input type="checkbox" tabindex="3" class="" name="remember" id="remember">
                                            <label for="remember"> Remember Me</label>
                                        </div>
                                    </div>
                                    <div class="col-md-6 col-6 text-right">
                                        <div class="res-box">
                                            <a href="#" tabindex="5" class="forgot-password">Forgot Password?</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="form-group">
                                    <div class="row">
                                        <div class="col-sm-6 col-sm-12">
                                            <div class="res-box">
                                                <input type="submit" name="login-submit" id="login-submit" tabindex="4" class="button style1" value="Log In">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </form>
                            <div class="social-profile-login text-center">
                                <h5>Or Login with</h5>
                                <ul class="social-buttons style2 mar-top-20">
                                    <li><a href="#"><i class="ion-social-facebook"></i></a></li>
                                    <li><a href="#"><i class="ion-social-twitter"></i></a></li>
                                    <li><a href="#"><i class="ion-social-instagram"></i></a></li>
                                    <li><a href="#"><i class="ion-social-linkedin"></i></a></li>
                                </ul>
                            </div>
                        </div>
                        <div class="tab-pane fade" id="register" role="tabpanel">
                            <form id="register-form" action="#" method="post">
                                <div class="form-group">
                                    <input type="text" name="user_name" id="user_name" tabindex="1" class="form-control" placeholder="Username" value="">
                                </div>
                                <div class="form-group">
                                    <input type="email" name="email" id="email" tabindex="1" class="form-control" placeholder="Email Address" value="">
                                </div>
                                <div class="form-group">
                                    <input type="password" name="user_password" id="user_password" tabindex="2" class="form-control" placeholder="Password">
                                </div>
                                <div class="form-group">
                                    <input type="password" name="confirm-password" id="confirm-password" tabindex="2" class="form-control" placeholder="Confirm Password">
                                </div>
                                <div class="form-group">
                                    <div class="row">
                                        <div class="col-sm-6 col-sm-offset-3">
                                            <input type="submit" name="register-submit" id="register-submit" tabindex="4" class="button style1" value="Register Now">
                                        </div>
                                    </div>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!--User login section endss-->
    <!--Scroll to top starts-->
    <a href="#" id="scrolltotop"><i class="ion-ios-arrow-thin-up"></i></a>
    <!--Scroll to top ends-->
    <!-- Footer section Starts-->
    <section class="footer-wrapper style1 footer-bg no-pad" style="background-image: url(images/footer/footer-3.jpg)">
        <div class="overlay op-7"></div>
        <div class="footer-top-area style2">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-md-3 col-xs-12 text-center">
                        <div class="social-link style1">
                            <ul class="social-btn style1">
                                <li><a href="#"><i class="ion-social-facebook"></i></a></li>
                                
                                <li><a href="#"><i class="active ion-social-twitter"></i></a></li>
                                <li><a href="#"><i class="ion-social-rss"></i></a></li>
                                <li><a href="#"><i class="ion-social-pinterest"></i></a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-md-6 col-xs-12 text-center">
                        <div class="footer-widget style1">
                            <ul class="footer-menu style1">
                                <li><a class="link-hov style3" href="#">Terms & Condition</a></li>
                                <li><a class="link-hov style3" href="#">Site map</a></li>
                                <li><a class="link-hov style3" href="#">Privacy policy</a></li>
                                <li><a class="link-hov style3" href="#">FAQ</a></li>
                                <li><a class="link-hov style3" href="#">Affiliate</a></li>
                            </ul>
                        </div>
                        <div class="copyright-area style1 mar-top-50">
                            <p><a href="#"><img src="images/logo-white.png" alt="..."></a><span>????</span> 2019 </p>
                        </div>
                    </div>
                    <div class="col-md-3 col-xs-12 text-center">
                        <div class="footer-widget style1">
                            <ul class="payment-opt style1">
                                <li> <a href="#"><img src="images/payment/payment-1.png" alt="..."></a></li>
                                <li> <a href="#"><img src="images/payment/payment-2.png" alt="..."></a></li>
                                <li> <a href="#"><img src="images/payment/payment-3.png" alt="..."></a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer section Ends-->
    <!--Plugin js -->
    <script src="js/plugin.js"></script>
    <!-- Main js -->
    <script src="js/main.js"></script>
</body>


</html>
