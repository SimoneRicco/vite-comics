<script>
export default {

}
</script>

<template>
  <div class="infos">
    <div class="container">
        <div class="info">
            <div class="img">
                <img src="../../img/buy-comics-digital-comics.png" alt="">
            </div>
            <div class="info-text">Digital Comics</div>
        </div>
        <div class="info">
            <img src="../../img/buy-comics-merchandise.png" alt="">
            <div class="info-text">DC Merchandise</div>
        </div>
        <div class="info">
            <img src="../../img/buy-comics-shop-locator.png" alt="">
            <div class="info-text">Subscription</div>
        </div>
        <div class="info">
            <img src="../../img/buy-comics-subscriptions.png" alt="">
            <div class="info-text">Comic Shop Locator</div>
        </div>
        <div class="info">
            <img src="../../img/buy-dc-power-visa.svg" alt="">
            <div class="info-text">DC Power Visa</div>
        </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.infos{
    background-color: dodgerblue;
    .container{
        display: flex;
        align-items: center;
        padding: 2rem 0;
        justify-content: space-around;
    }
    .info-text{
        text-transform: uppercase;
        color: white;
    }
    img{
        width: 75px;
    }
    .info{
        display: flex;
        align-items: center;
    }
}
</style>