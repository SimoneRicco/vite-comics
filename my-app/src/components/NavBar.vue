<template>
    <ul>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>Tv</li>
        <li>Ganes</li>
        <li>Colletibles</li>
        <li>Videos</li>
        <li>Fans</li>
        <li>News</li>
        <li>Shop</li>
    </ul>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
ul{
    list-style: none;
    display: flex;
    gap: 1rem;
    align-items: center;
    li{
        text-transform: uppercase;
        &:hover{
            color: blue;
        }
    }
}
</style>