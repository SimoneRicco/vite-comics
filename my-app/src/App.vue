<script>
import ContentVue from './components/Content.vue';
import Header from './components/Header.vue';
import Info from './components/Info.vue';
export default {
  components: {
    Header,
    ContentVue,
    Info,
  }
}
</script>

<template>
  <div>
    <Header></Header>
    <ContentVue></ContentVue>
    <Info></Info>
  </div>
</template>

<style>

</style>