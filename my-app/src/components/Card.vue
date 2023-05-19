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
        </div>
        <div class="title">{{ series }}</div>
    </div>
</template>

<style lang="scss" scoped>
    .image{
        width: 100px;
        height: 100px;
        img{
            width: 100%;
            height: 100%;
        }
        
    }
    .card{
        color: white;
        word-wrap: break-word;
    }
</style>