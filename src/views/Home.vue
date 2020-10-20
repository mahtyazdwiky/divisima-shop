<template>
  <div class="home">
    <Header/>
    <Hero/>
    <Features/>
    <RelatedProduct/>
    <TopSelling/>
    <Banner/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import Features from '@/components/Features.vue'
import RelatedProduct from '@/components/RelatedProduct.vue'
import TopSelling from '@/components/TopSelling.vue'
import Banner from '@/components/Banner.vue'
import Footer from '@/components/Footer.vue'






export default {
  name: 'Home',
  components:{
    Header,
    Hero,
    Features,
    RelatedProduct,
    TopSelling,
    Banner,
    Footer
  }

}
</script>
