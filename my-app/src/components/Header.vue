<script>
import NavBar from './NavBar.vue';
export default {
    components: {
        NavBar
    }
}
</script>

<template>
    <header>
        <div class="container">
            <div class="header-icon">
                <img src="../../img/dc-logo.png" alt="">
            </div>
          <NavBar></NavBar>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header{
    .container{
        display: flex;
        justify-content: space-between;
        padding: 1rem 0;
    }
}
</style>