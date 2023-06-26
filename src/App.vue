<template>
  <HeaderComVue></HeaderComVue>
  <BannerComVue></BannerComVue>
  <AboutComVue></AboutComVue>
  <ServiceComVue></ServiceComVue>
  <ProComVue></ProComVue>
  <ReviewComVue></ReviewComVue>
  <ContactComVue></ContactComVue>
  <FooterComVue></FooterComVue>
</template>

<script>
import HeaderComVue from './components/HeaderCom.vue';
import BannerComVue from './components/BannerCom.vue';
import AboutComVue from './components/AboutCom.vue';
import ServiceComVue from './components/ServiceCom.vue';
import ProComVue from './components/ProCom.vue';
import ReviewComVue from './components/ReviewCom.vue';
import ContactComVue from './components/ContactCom.vue';
import FooterComVue from './components/FooterCom.vue';
export default {
  name: 'App',
  components: {
    HeaderComVue,
    BannerComVue,
    AboutComVue,
    ServiceComVue,
    ProComVue,
    ReviewComVue,
    ContactComVue,
    FooterComVue
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
