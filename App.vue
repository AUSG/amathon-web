<template>
  <div class="app">
    <Top />
    <Hero />
    <Amathon />
    <AWSKRUG />
    <AUSG />    
    <RegisterButton />
  </div>
</template>

<script>
import Top from './components/Top.vue'
import RegisterButton from './components/RegisterButton.vue'
import Hero from './components/Hero.vue'
import AWSKRUG from './components/AWSKRUG.vue'
import AUSG from './components/AUSG.vue'
import Amathon from './components/Amathon.vue'

export default {
  components: {
    Top,
    Hero,
    RegisterButton,
    AWSKRUG,
    AUSG,    
    Amathon,
  },
}
</script>