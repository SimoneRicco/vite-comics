<script>
export default {

}
</script>

<template>
    <div class="product-list">
        <div class="container myList">
            <div class="col1">
                <ul>
                    <li class="list-title">DC Comics</li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <ul>
                    <li class="list-title">Shop</li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
            <div class="col2">
                <ul>
                    <li class="list-title">DC</li>
                    <li>Terms Of Use</li>
                    <li>Privacy polici (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Contact Us</li>
                </ul>
            </div>
            <div class="col3">
                <ul>
                    <li class="list-title">Sites</li>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
        </div>
        <div class="container">
            <div class="background-image">
                <img src="../../img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
ul{
    list-style: none;
    margin-bottom: 1rem;
    li{
        color: gray;
        
    }
    .list-title{
        color: white;
        text-transform: uppercase;
        font-size: 1.5rem;
        margin-bottom: .5rem;
    }
}
.product-list{
    background-image: url("../../img/footer-bg.jpg");
    display: flex;
    justify-content: space-between;
}
.myList{
    padding: 2rem 0;
    display: flex;
    gap: 2rem;
}
.background-image{
    //qua non funziona
    img{
        object-fit: cover;
    }
}
</style>