<script>
export default {
    props: {
        imgLink: String,
        price: String,
        series: String,
        tyoe: String,
    }
}
</script>

<template>
    <div class="card">
        <div class="image">
            <img :src="imgLink" alt="Card">
            <!-- <img src="https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg" alt="Card"> -->
        </div>
        <div class="title">{{ series }}</div>
    </div>
</template>

<style lang="scss" scoped>
    .image{
        width: 100%;
        height: 80%;
        img{
            width: 100%;
            height: 100%;
        }
    }
    .card{
        color: white;
        word-wrap: break-word;
        width: calc(100% / 6 - 2rem);
        height: 200px;
        margin-bottom: 2rem;
    }
</style>