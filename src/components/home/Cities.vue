<template>
        <div class="row" style="margin-left:120px;margin-right:50px;">
           
        <div style="margin-top:65px;">
             <i class="fa fa-arrow-left" style="color:gray;font-size:24px;" aria-hidden="true"></i>
           </div>
           <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/delhi_ncr-min.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Delhi</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/hyderabad-min.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Hyderabad</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/kanpur-min.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Kanpur</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/lucknow-min.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Lucknow</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/lucknow-min.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Lucknow</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/mumbai-min.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Mumbai</a></b></p>
            </div>
            <div class="transitionTransform">
            <img src="http://www.roundthecorner.in/wp-content/uploads/2016/06/mumbai-min.jpg" alt="Grocery" data-description="" style="border-radius: 150px;border: 5px solid #dddddd !important;height: 120px !important;width: 120px !important;display: inline-block !important;width: 100%; height: auto; max-width: 100%; max-height: none; margin-top: 14px; margin-left: 0px;">
            <br>
             <p class="product-p"><b class="hover-effects"><a>Mumbai</a></b></p>
            </div>
            <div style="margin-top:65px;margin-left:12px;">
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