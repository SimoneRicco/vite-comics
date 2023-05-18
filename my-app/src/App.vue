<script>
import ContentVue from './components/Content.vue';
import DcProducts from './components/DcProducts.vue';
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
import Info from './components/Info.vue';
export default {
  components: {
    Header,
    ContentVue,
    Info,
    DcProducts,
    Footer
  }
}
</script>

<template>
  <div>
    <Header></Header>
    <ContentVue></ContentVue>
    <Info></Info>
    <DcProducts></DcProducts>
    <Footer></Footer>
  </div>
</template>

<style>

</style>