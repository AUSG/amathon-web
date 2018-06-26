<template>
  <div class="top">
    <a href="#" class="top__logo">
      <img src="../assets/top-logo.svg" />
    </a>
    <div class="top__space"></div>
    <nav>
      <a href="#amathon">Amathon</a>
      <a href="#awskrug">AWSKRUG</a>
      <a href="#ausg">AUSG</a>      
    </nav>
    <a class="top__button" @click="apply">
      <img src="../assets/clipboard.svg" />
      <label>지원하기</label>
    </a>
  </div>
</template>

<script>
export default {
  methods: {
    apply() {
      window.alert('7/2에 오픈됩니다')
    },
  },
}
</script>