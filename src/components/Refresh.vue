<template>
  <div class="refresh">
    <button class="refreshBtn" @click="clickHandler()">Refresh</button>
  </div>
</template>

<script>
export default {
    name: 'RefreshBtn',
    methods: {
        clickHandler() {
            window.location.reload();
        }
    }
}
</script>

<style scoped>
    .refresh {
        grid-column: 2;
        z-index: 1;
        grid-row: 3;
        opacity: 1;
        margin: 5px;

    }
    .refreshBtn {
        border: var(--main-color-two) 3px solid;
        border-radius: 0.3rem;
        background: var(--main-color-one);
        padding: 1rem 3rem 1rem 3rem;
        color: var(--main-color-four);
        font-weight: 600;
        font-size: 2rem;
        box-shadow: 0 0 10px var(--main-color-one);

    }
</style>