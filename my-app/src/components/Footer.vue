<script>
export default {

}
</script>

<template>
  <footer>
    <div class="container">
        <div class="button">
            <a href="#">Sing-Up Now!</a>
        </div>
        <div class="socials">
            <div class="follow">Follow Us</div>
            <img src="../../img/footer-facebook.png" alt="">
            <img src="../../img/footer-twitter.png" alt="">
            <img src="../../img/footer-youtube.png" alt="">
            <img src="../../img/footer-pinterest.png" alt="">
            <img src="../../img/footer-periscope.png" alt="">
        </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer{
    background-color: rgb(33, 33, 33);
}
.container{
    display: flex;
    padding: 2rem 0;
    justify-content: space-between;
}
.button{
    border: 2px solid blue;
    padding: 8px 16px;
    a{
        color: white;
        text-decoration: none;
    }
}
.follow{
    color: dodgerblue;
}
.socials{
    display: flex;
    gap: 2rem;
    img{
        flex: 0 0 auto;
    }
}
</style>