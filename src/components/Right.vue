<template>
    <div class="right">
        <img src="https://media2.giphy.com/media/l4pTldWDec8WamJUc/giphy.gif?cid=ecf05e47kk7ftsweshesmw02li6zzznwswi3wt1xi3yjkc1e&ep=v1_gifs_search&rid=giphy.gif&ct=g" alt="Landing Rocket">
    </div>
</template>

<script>
export default {
    name: "LandingRocket",
}
</script>

<style scoped>
    .right {
        grid-row: 1 / 4;
        grid-column: 3;
        z-index: 1;
    }
    .right > img {
        width: 5rem;
        height: 100%;
        object-fit: cover;
        box-shadow: 0 0 10px var(--main-color-one);
    }
</style>