<template>
  <div id="app">
      <app-headers></app-headers>
      <a id="scroll"><i class="fa fa-arrow-up" aria-hidden="true"></i></a>
      <router-view></router-view>
      <app-footer></app-footer>  
  </div>
</template>

<script>
import Header from "./components/header/Header.vue";
import Footer from "./components/footer/Footer.vue";
$(document).ready(function(){ 
    $(window).scroll(function(){ 
        if ($(this).scrollTop() > 100) { 
            $('#scroll').fadeIn(); 
        } else { 
            $('#scroll').fadeOut(); 
        } 
    }); 
    $('#scroll').click(function(){ 
        $("html, body").animate({ scrollTop: 0 }, 1300); 
        return false; 
    }); 
});
export default {
  components: {
    "app-headers": Header,
    "app-footer": Footer
  },
  name: "App"
};
</script>

 <style>
 #scroll {
    text-align: center;
    position:fixed;
    right:30px;
    bottom:9%;
    cursor:pointer;
    width:30px;
    height:30px;
    background-color:#db0056;
    color:white;
}
#scroll i {
  font-size: 14px;
  margin: 7px 0 0 0px;
}

</style>