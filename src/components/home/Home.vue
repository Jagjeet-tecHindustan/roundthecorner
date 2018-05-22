<template>
<div id="Home">

  <div class="intro">
        <div class="divider-150"></div>
        <div class="row" style="margin-left: 0px;margin-right: 0px;">
          <div class="col-md-5" style="margin-top:90px;margin-left: 70px;">
              
              <div class="intro-header">
                  <h1>
                    <strong style="color: #fff;">
                      Great things are just <br /> 
                      <span style="color: #e1e35c;">
                        Round the Corner!
                      </span>
                    </strong>
                  </h1>
              </div>

              <div class="intro-header">
                    <h4>
                      <span style="color: #ffffff;">
                        Get 15% Off On Your First Purchase! Use Code xxxx!
                      </span>
                    </h4>

                    <h3 style="color: #ffffff;">
                      Download App Now!
                    </h3>
              </div>

              <div class="divider"></div><div class="divider"></div>

              <div class="intro-header">
                <form>
                  <div class="row" style="margin-left: 0px;margin-right: 0px;">
                      <input type="text"  v-model="phone" id="formInput" placeholder="Enter Phone Number" class="form-control">
                      <button id="formButton" @click.prevent="getError">Get App</button>
                  </div>
                  <div class="divider"></div><div class="divider"></div>
                  <span class="getapperror" v-if="error"><b>{{msg}}</b></span>
                </form>
              </div>

              <div class="divider"></div><div class="divider"></div><div class="divider"></div>

              <p>
                <a href="#">
                  <img class="alignnone wp-image-70" src="http://www.roundthecorner.in/wp-content/uploads/2015/06/google.png" width="169" height="50"></a>&nbsp;&nbsp; <a href="#"><img class="alignnone wp-image-71" src="http://www.roundthecorner.in/wp-content/uploads/2015/06/apple.png" width="167" height="50">
                </a>
              </p>

          </div>

          <div class="col-md-6">
            <img style="width:638px;height:525px;margin-left:65px;" class="img-responsive" src="http://www.roundthecorner.in/wp-content/uploads/2015/06/hand_bg.png" alt="hand_bg" srcset="http://www.roundthecorner.in/wp-content/uploads/2015/06/hand_bg.png 694w, http://www.roundthecorner.in/wp-content/uploads/2015/06/hand_bg-300x267.png 300w, http://www.roundthecorner.in/wp-content/uploads/2015/06/hand_bg-420x374.png 420w" >
          </div>
        </div>  

  </div>

    <div class="why-roundCorner">  
            <div class="divider"></div><div class="divider"></div><div class="divider"></div>
            <h1><strong>Why <span style="color: #db0056;">Round The Corner</span></strong></h1>
            <div class="divider"></div>
            <div class="row" style="margin-left:70px;margin-right:70px;">
                <p>We at Round The Corner take pride in our stringent quality standards. We go to great lengths and take the utmost care and precaution to ensure that each day our customers get nothing but the very best across all our products, services &amp; interactions.<br>
              At Round The Corner, we offer an extensive assortment of 45000 + More products that include Groceries, Fruits and Vegetables, Personal Care Products, Electronics, Flowers, Bakery items, Pet Products and much more through our offline and online stores.</p>    
            </div>
    </div> 

    <div class="appProducts">
      <div class="divider"></div><div class="divider"></div><div class="divider"></div>
      <h2><strong>A Wide Range Of <span style="color: #db0056;">Products</span></strong></h2>
      <app-product></app-product>
    </div>


    <div class="appFeatures">
       <div class="divider"></div><div class="divider"></div><div class="divider"></div>
       <h2><strong>App <span style="color: #db0056;">Features</span></strong></h2>
    </div>

    <div class="main-features">
     <div class="divider"></div><div class="divider"></div><div class="divider"></div>
      <div class="row" style="margin-left:70px;margin-right:70px;">
        <div class="col-md-4 col-xs-12" id="main-features-left">
          <div>
            <i class="vc_icon_element-icon fa fa-adjust"></i><br><br><br>
            <p style="text-align: right;"><strong>Collection Items</strong><br>
              <span style="font-size:13px;">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
              </span>
            </p>  
        </div>

        <div><div class="divider"></div>
            <i class="vc_icon_element-icon fa fa-picture-o"></i><br><br><br>
            <p style="text-align: right;"><strong>Latest Products</strong><br>
              <span style="font-size:13px;">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
              </span>
            </p>  
        </div>

        <div><div class="divider"></div>
            <i class="vc_icon_element-icon fa fa-cog"></i><br><br><br>
            <p style="text-align: right;"><strong>24*7 Days Support</strong><br>
              <span style="font-size:13px;">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
              </span>
            </p>  
        </div>

        </div>

        <div class="col-md-4 col-xs-12">
            <img width="421" height="739" src="http://www.roundthecorner.in/wp-content/uploads/2015/06/mobile.jpg" class="img-responsive-product" alt="mobile" srcset="http://www.roundthecorner.in/wp-content/uploads/2015/06/mobile.jpg 421w, http://www.roundthecorner.in/wp-content/uploads/2015/06/mobile-171x300.jpg 171w, http://www.roundthecorner.in/wp-content/uploads/2015/06/mobile-420x737.jpg 420w" sizes="(max-width: 421px) 100vw, 421px">
        </div>

        <div class="col-md-4 col-xs-12" id="main-features-right">
            <div>
                <i class="vc_icon_element-icon fa fa-font"></i>
                <div class="divider"></div><div class="divider"></div>
                <p><strong>720+ Products</strong><br>
                  <span style="font-size:13px;">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
                  </span>
                </p>  
            </div>       

            <div>
                <i class="vc_icon_element-icon fa fa-diamond"></i>
                <div class="divider"></div><div class="divider"></div>
                <p><strong>Pure & Fresh</strong><br>
                  <span style="font-size:13px;">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
                  </span>
                </p>  
            </div>

            <div>
                <div class="divider"></div><div class="divider"></div>
                <i class="vc_icon_element-icon fa fa-gift"></i>
                <div class="divider"></div><div class="divider"></div>
                <p><strong>More Features</strong><br>
                  <span style="font-size:13px;">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
                  </span>
                </p>  
            </div>

        </div>
      </div>
    </div>

    <div class="row" style="margin-left:70px;margin-right:70px;">
      <div class="col-md-6 col-xm-12">
        <img width="382" height="409" src="http://www.roundthecorner.in/wp-content/uploads/2015/06/single-img.png" class="img-responsive-productCart" alt="single-img" srcset="http://www.roundthecorner.in/wp-content/uploads/2015/06/single-img.png 382w, http://www.roundthecorner.in/wp-content/uploads/2015/06/single-img-280x300.png 280w" sizes="(max-width: 382px) 100vw, 382px">
      </div>

       <div class="col-md-6 col-xm-12">
         <div style="margin-top:112px;margin-left:13px;">
           <h1 style="font-size:30px;">Shop from your favorite stores</h1> 
           <p style="font-size:16px;"><br><br>
           Shop for products of your choice from your favorite local stores and get everything delivered to your doorstep.
           </p>
           <br><br>
            <button type="button" class="btn btn-default" style="background: #db0056 !important;border-radius:8px;">More Defaults</button>
         </div>
      </div>
      
    </div>

    <div class="row" style="margin-left:70px;margin-right:70px;margin-top:55px;">
      <div class="col-md-6 col-xm-12" style="margin-top: 100px;">
        <h1 style="font-size:30px;">
          Add products to cart
        </h1>
        <p style="font-size:16px;font-family:Dosis;color:#4f4f4f;"><br><br>
        We Love Your Choice, so we don’t want you to miss out anything. Build your cart by adding items. You can club products from different stores and categories.
        </p>
        <br><br>
            <button type="button" class="btn btn-default" style="background: #db0056 !important;border-radius:8px;">More Defaults</button>
      </div>
      <div class="col-md-4 col-xm-12 offset-md-2">
          <img width="382" height="409" src="http://www.roundthecorner.in/wp-content/uploads/2015/06/signle-img2.png" class="img-responsive-productCart" alt="signle-img2" srcset="http://www.roundthecorner.in/wp-content/uploads/2015/06/signle-img2.png 382w, http://www.roundthecorner.in/wp-content/uploads/2015/06/signle-img2-280x300.png 280w" sizes="(max-width: 382px) 100vw, 382px">
      </div>
    </div>

    <div><div class="divider"></div><div class="divider"></div>
      <h1 style="font-size:35px;text-align:center;">Speedy and Scheduled Deliveries</h1>
    </div>
    <div style="margin-left:70px;margin-right:70px;margin-top:25px;">
      <p style="font-size:15px;text-align:center;">
        You can be sure that you will get the best quality level of products at the right time<br> and at the right place.We understand the importance of your time.
      </p>
       
    </div>

    <div>
     <div class="divider"></div><div class="divider"></div>
         <h1 style="text-align: center; color: #454545; font-size: 32px;"><strong><span style="color: #db0056;">Cities</span></strong></h1>
         <app-cities></app-cities>
    </div>


  <div>
    <div class="divider"></div>
         <h1 style="text-align: center; color: #454545; font-size: 32px;"><strong>Download <span style="color: #db0056;"> App</span></strong></h1>
      <p style="font-size:15px;text-align:center;"><br>
        Download our mobile app and get everything delivered to your doorstep, quickly.
      </p>
      <br>
      <div style="text-align:center;">
        <img class="wp-image-70 alignleft" src="http://www.roundthecorner.in/wp-content/uploads/2015/06/google.png" width="169" height="50">
        <img style="margin-left:15px;" src="http://www.roundthecorner.in/wp-content/uploads/2015/06/apple.png" width="167" height="50">
        <br><br>
        <img width="680" height="160" src="http://www.roundthecorner.in/wp-content/uploads/2015/06/img4.png" class="img-responsive-mobile" alt="img4" srcset="http://www.roundthecorner.in/wp-content/uploads/2015/06/img4.png 680w, http://www.roundthecorner.in/wp-content/uploads/2015/06/img4-300x71.png 300w, http://www.roundthecorner.in/wp-content/uploads/2015/06/img4-420x99.png 420w" sizes="(max-width: 680px) 100vw, 680px">
      </div>
  </div>
    

    </div>
</template>

<script>
import Cities from "./Cities.vue";
import Product from "./Product.vue";
export default {
  components: {
    "app-cities": Cities,
    "app-product": Product
  },
  name: "Home",
  data() {
    return {
      error: false,
      phone: "",
      msg: ""
    };
  },
  methods: {
    getError() {
      this.error = true;
      if (this.phone.length > 9) {
        this.msg = "We have sent you a SMS with download link";
      } else {
        this.msg = "Please Enter Valid Number";
      }
    }
  }
};
</script>

<style>
.intro {
  background-image: url(http://www.roundthecorner.in/wp-content/uploads/2015/06/banner-home02.jpg?id=33180) !important;
  background-size: cover;
}
intro-header {
  margin-bottom: 30px;
}
.intro-header h1 {
  font-family: Dosis;
  line-height: normal;
  font-size: 46px;
}
.intro-header h4 {
  font-family: Dosis;
  font-weight: 400;
  text-transform: none;
  letter-spacing: 1.25px;
}
.divider-150 {
  height: 150px;
}
.divider {
  height: 10px;
}
#formInput {
  width: 50% !important;
  border-radius: 0 !important;
  border-top-left-radius: 0;
  background: #fff;
  height: 50px;
  border: none !important;
}
#formButton {
  background: #d91762;
  text-transform: capitalize;
  height: 50px;
  border: none !important;
  color: white;
  line-height: normal;
  padding: 0em 1.875em;
  font-size: 20px;
}
.getapperror {
  display: block;
  border: 1px dashed #db0056;
  color: #fff;
  padding: 7px;
  width: 413px;
  font-size: 14px;
}
.why-roundCorner h1 {
  text-align: center;
  color: #454545;
  font-size: 32px;
}
.why-roundCorner p {
  text-align: center;
  font-size: 16px;
}
.appProducts h2 {
  text-align: center;
  color: #454545;
  font-size: 32px;
}
.appFeatures h2 {
  text-align: center;
  color: #454545;
  font-size: 32px;
}
#main-features-left i {
  color: #db0056 !important;
  float: right;
  font-size: 40px;
}
#main-features-right i {
  color: #db0056 !important;
  font-size: 40px;
}
#wonderplugincarousel-2 .amazingcarousel-image {
  position: relative;
  padding: 0px;
}
@media only screen and (max-width: 600px) {
  .img-responsive {
    width: 280px !important;
    height: 250px !important;
  }
  .img-responsive-mobile {
    width: 290px !important;
    height: 100px !important;
  }
  .img-responsive-product {
    width: 270px !important;
    height: 400px !important;
  }
  .img-responsive-productCart {
    width: 250px !important;
    height: 250px !important;
  }
}
</style>