<script>
import ContentVue from './components/Content.vue';
import DcProducts from './components/DcProducts.vue';
import Header from './components/Header.vue';
import Info from './components/Info.vue';
export default {
  components: {
    Header,
    ContentVue,
    Info,
    DcProducts
  }
}
</script>

<template>
  <div>
    <Header></Header>
    <ContentVue></ContentVue>
    <Info></Info>
    <DcProducts></DcProducts>
  </div>
</template>

<style>

</style>