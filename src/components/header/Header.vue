<template>
    <header>
        <nav class="navbar fixed-top navbar-expand-lg navbar-dark scrolling-navbar">
                <a class="navbar-brand" href="#">
                  <img src="http://www.roundthecorner.in/wp-content/uploads/2015/06/logo.png" alt="" /></a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav mr-auto"></ul>
                    <ul class="navbar-nav">
                    <li class="nav-item">
                      <router-link active-class="active" to="/home" class="nav-link" tag="a">
                        HOME
                      </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link active-class="active" to="/about" class="nav-link" tag="a">
                          ABOUT US
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link">GET YOUR STORE STORE LISTED</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link">CONTACT US</a>
                    </li>
                    
                    <li class="nav-item-icon">
                         <a class="nav-link" data-toggle="modal" data-target="#modalPoll"> <i class="fa fa-bars" aria-hidden="true"></i></a>
                         <!-- Modal: modalPoll -->
                            <div class="modal fade right" id="modalPoll" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true"
                              data-backdrop="false">
                              <div class="modal-dialog modal-full-height modal-right modal-notify modal-info" role="document">
                                <div class="modal-content" style="margin-left:137px;">   
                                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                      <span aria-hidden="true" class="black-text">×</span>
                                    </button>
                                    <ul style="color:black;margin-top:40px;list-style-type:none;line-height:2;font-weight:bold;">
                                      <li>CAREERS<li>
                                      <li>OUR TEAM</li>
                                      <li>TESTIMONIALS</li>
                                      <li>BLOGS</li>
                                      <li>FAQS</li>
                                      <li>PRIVACY POLICY</li>
                                      <li>TERMS AND CONDITIONS</li>
                                      <li>SITE MAP</li>
                                    </ul>
                                </div>
                              </div>
                            </div>
                   
                    </li>

                </ul>
                </div>
            </nav>
    </header>
            
</template>

<script>
export default {
};
</script>

<style>
.nav-link.active {
  color: gray !important;
}
.navbar {
  box-shadow: none !important;
  background-color: transparent;
}
.navbar-brand {
  margin-left: 70px;
  margin-top: 14px;
}
.nav-link {
  color: white !important;
  line-height: 1.875;
    font-family: Karla;
        font-size: 14px;
    font-weight: 200;
}
.nav-item a:hover {
  color: #d91762 !important;
}
.nav-item-icon a:hover {
  color: gray !important;
}
.top-nav-collapse {
  background-color: #111213;
}
.active-class {
  color: blue;
}
.navbar.scrolling-navbar.top-nav-collapse {
  height: 67px;
}
.navbar.scrolling-navbar.top-nav-collapse img {
  height: 30px;
  margin-bottom: 15px;
}

@media only screen and (max-width: 768px) {
  .navbar {
    background-color: #111213;
  }
}
.navbar,
.pagination .page-item.active .page-link {
  -webkit-box-shadow: none;
}

.navbar-nav {
  margin-right: 70px;
  font-size: 13px;
  letter-spacing: 1px;
  margin-top: 0px;
}

@media only screen and (max-width: 600px) {
  .navbar-brand {
    margin-left: 10px !important;
    margin-top: 14px;
  }
  .navbar {
    background-color: #111213;
  }
  .top-nav-collapse {
    background-color: #111213;
  }
}
</style>