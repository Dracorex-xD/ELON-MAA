<template>
    <div class="face">
    </div>
  </template>
  
  <script>
  export default {
    name: "ElonMuskFace",
  }
  </script>
  
  <style scoped>
      .face {
        grid-row: 1 / 4;
        grid-column: 1 / 4;
        background: linear-gradient(var(--main-color-five), var(--main-color-four));
        opacity: 0.7;

      }
      .face > img {
          z-index: -69;
          width: 25rem;
          height: 38.8rem;
          opacity: 0.5;
      }
  </style>