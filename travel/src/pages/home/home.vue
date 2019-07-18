<template>
   <div>
     <Header></Header>
     <swiper></swiper>
   </div>
</template>

<script>
  import Header from "../../pages/home/components/Header"
  import Swiper from "../../pages/home/components/Swiper"
    export default {
        name: "home",
      components:{
          Header,
          Swiper
      }
    }
</script>

<style scoped>

</style>
