<template>
  <div class="hero" :style="heroStyle">
  </div>
</template>

<script>
export default {
  data: () => ({
    heroStyle: {
      backgroundImage: `url(${require('../assets/hero.svg')}`,
    },
  }),
}
</script>