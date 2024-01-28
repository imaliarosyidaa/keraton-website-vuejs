<script setup>
  import Header from './views/Header.vue'
  import Tentang from './views/Tentang.vue'
  import Youtube from './views/Youtube.vue'
  import Sejarah from './views/Sejarah.vue'
  import Event from './views/Event.vue'
  import ObjectWisata from './views/ObjectWisata.vue'
  import Faq from './views/Faq.vue'
  import Footer from './views/Footer.vue'
</script>

<template>
  <section>
    <Header/>
    <Tentang/>
    <Youtube/>
    <Sejarah/>
    <Event/>
    <ObjectWisata/>
    <Faq/>
    <Footer/>
  </section>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>

</style>
