<template>
  <div class="app">
    <Top />
    <Hero />
    <AUSG />
    <RegisterButton />
  </div>
</template>

<script>
import Top from './components/Top.vue'
import RegisterButton from './components/RegisterButton.vue'
import Hero from './components/Hero.vue'
import AUSG from './components/AUSG.vue'

export default {
  components: {
    Top,
    Hero,
    RegisterButton,
    AUSG,
  },
}
</script>