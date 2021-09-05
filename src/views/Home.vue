<template>
  <div class="home">
    <Header />
    <CarouselShayna />
    <CarouselProduct />
    <InstaShayna />
    <LogoPartner />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";
import CarouselShayna from "@/components/CarouselShayna.vue";
import CarouselProduct from "@/components/CarouselProduct.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import LogoPartner from "@/components/LogoPartner.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    CarouselShayna,
    CarouselProduct,
    InstaShayna,
    LogoPartner,
    Footer,
  },
};
</script>
