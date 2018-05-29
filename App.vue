<template>
  <div class="app">
    <Top />
    <Hero />
    <AUSG />
    <AWSKRUG />
    <Hackathon />
    <RegisterButton />
  </div>
</template>

<script>
import Top from './components/Top.vue'
import RegisterButton from './components/RegisterButton.vue'
import Hero from './components/Hero.vue'
import AUSG from './components/AUSG.vue'
import AWSKRUG from './components/AWSKRUG.vue'
import Hackathon from './components/Hackathon.vue'

export default {
  components: {
    Top,
    Hero,
    RegisterButton,
    AUSG,
    AWSKRUG,
    Hackathon,
  },
}
</script>