<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <FirstStep/>
  </div>
</template>

<script>
// @ is an alias to /src
import FirstStep from '@/components/FirstStep.vue'

export default {
  name: 'HomeView',
  components: {
    FirstStep,
  }
}
</script>
