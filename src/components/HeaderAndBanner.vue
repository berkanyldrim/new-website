<template>
    <!---header-and-banner-section-->
      <div class="header-and-banner-con w-100 float-left position-relative">
         <div class="header-and-banner-inner-con">
             <HeaderComp></HeaderComp>
             <BannerComp></BannerComp>
         </div>
      </div>
</template>

<script>
import HeaderComp from "./HeaderAndBannerComponents/HeaderComp.vue";
import BannerComp from "./HeaderAndBannerComponents/BannerComp.vue";

export default{
    name:"HeaderAndBanner",
    components: {
    HeaderComp,
    BannerComp,
}

}

</script>