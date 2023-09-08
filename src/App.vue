<template>
  <div class="main-layout">
    <div class="main-layout__wrap">
      <heading text="Find your music match" counter="1"></heading>
    </div>
  </div>
</template>

<script>
import Heading from './components/Heading.vue';
export default {
  components: {
    Heading,
  },
};
</script>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

html {
  font-size: 0.625em;
  box-sizing: border-box;
  text-size-adjust: 100%;
  text-rendering: optimizeSpeed;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}

body {
  font-family: 'Roboto', sans-serif;
  font-size: 1.6rem;
  color: rgba(0, 0, 0, 0.87);
  line-height: normal;
  background: #fafafa;
  min-height: 100vh;
  overflow-x: hidden;
  margin: 0;
}

.main-layout {
  min-height: 100vh;
  padding-top: 100px;
  padding-bottom: 50px;

  &__wrap {
    max-width: 74rem;
    padding: 0 20px;
    margin: 0 auto;
  }
}

@media only screen and (max-width: 600px) {
  .main-layout {
    padding-top: 50px;
  }
}
</style>
