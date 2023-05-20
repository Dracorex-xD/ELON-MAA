<template>
    <div class="score">
      <div class="title">ELON MAA </div>
      <div class="actaul-score">69</div>
    </div>
  </template>
  
  <script>
  export default {
      name: "ElonMaaScore",
  }
  </script>
  
  <style scoped>
    .score {
        grid-column: 2;
        grid-row: 1;
        color: var(--main-color-four);
        z-index: 1;
    }

    .title {
        font-size: 2rem;
        font-weight: 700;
    }
    .actaul-score {
        font-size: 5rem;

    }
  </style>