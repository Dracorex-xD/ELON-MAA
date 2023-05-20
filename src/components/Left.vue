<template>
    <div class="left">
        <img src="https://i.giphy.com/media/6njwjiMsRUS4tS9xm3/giphy.webp" alt="Rocket Explosion">
    </div>
</template>

<script>
export default {
    name: "ElonMuskRocketLeft",
}
</script>

    <style scoped>
    .left {
        grid-row: 1 / 4;
        grid-column: 1;
        z-index: 1;
        
    }
    .left > img {
        width: 5rem;
        height: 100%;
        object-fit: cover;
        box-shadow: 0 0 10px var(--main-color-one);

    }
</style>