<template>
    <div class="row" style="margin-left:120px;margin-right:50px;">
           <div style="margin-top:58px;">
             <i class="fa fa-arrow-left" style="color:gray;font-size:24px;" aria-hidden="true"></i>
           </div>
           <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/img8.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Flower</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/img7.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Meats</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/img6.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Cosmetic</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/img5.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Bakery</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/img4.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Pet Care</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/img3.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Electronics</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/img2.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Grocery</a></b></p>
            </div>
            <div style="margin-top:65px;margin-left:15px;">
             <i class="fa fa-arrow-right" style="color:gray;font-size:24px;" aria-hidden="true"></i>
           </div>
         </div>
</template>
<script>
export default {};
</script>

<style>
.transitionTransform {
  width: 130px;
  margin-left: 15px;
}

.transitionTransform img:hover {
    -webkit-transform: rotate(360deg);
    transform: rotate(360deg);
    transform: rotate(-360deg);
    transition: all 0.5s ease 0s;
    -webkit-transform: rotate(-360deg);
    -webkit-transition: all 0.5s ease 0s;
    cursor: pointer;
}
.product-p {
  color: #9e9e9e;
  font-size: 15px;
  font-family: "Ubuntu";
  font-weight: 500;
  text-align:center;
  margin-top:7px;
}
.product-p .hover-effects a:hover {
  color: #db0056;
}
</style>