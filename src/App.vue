<template>
  <div class="container">
    <Left />
    <Face />
    <Score />
    <Right />
    <Refresh />
  </div>
</template>

<script>
import Face from './components/Face.vue'
import Left from './components/Left.vue'
import Right from './components/Right.vue'
import Score from './components/Score.vue'
import Refresh from './components/Refresh.vue'

export default {
  name: 'App',
  components: {
    Face,
    Left,
    Right,
    Score,
    Refresh,
  }
}
</script>

<style>
    /*
    1. Use a more-intuitive box-sizing model.
  */
  *, *::before, *::after {
    box-sizing: border-box;
  }

  /*
    2. Remove default margin
  */
  * {
    margin: 0;
  }

  /*
    3. Allow percentage-based heights in the application
  */
  html, body {
    height: 100%;
  }

  /*
    Typographic tweaks!
    4. Add accessible line-height
    5. Improve text rendering
  */
  body {
    line-height: 1.5;
    -webkit-font-smoothing: antialiased;
  }

  /*
    6. Improve media defaults
  */
  img, picture, video, canvas, svg {
    display: block;
    max-width: 100%;
  }

  /*
    7. Remove built-in form typography styles
  */
  input, button, textarea, select {
    font: inherit;
  }

  /*
    8. Avoid text overflows
  */
  p, h1, h2, h3, h4, h5, h6 {
    overflow-wrap: break-word;
  }

  /*
    9. Create a root stacking context
  */
  #root, #__next {
    isolation: isolate;
  }

  :root {
    --main-color-one: #608faf;
    --main-color-two: #b99074;
    --main-color-three: #a493bd;
    --main-color-four: #655879;
    --main-color-five: #46424d;

  }

  body {
    overflow: visible;

  }

.container {

  display: grid;
  text-align: center;
  border: 10px solid var(--main-color-two);
  background: url("https://pngimg.com/uploads/elon_musk/elon_musk_PNG37.png") right no-repeat;
  font-family: Arial, Helvetica, sans-serif;
  box-shadow: 0 0 10px inset var(--main-color-one);
  z-index: -2;

  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(3, 1fr);
  
  width: 25rem;
  height: 40rem;
}

</style>
