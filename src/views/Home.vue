<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Live2d></Live2d>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Live2d from '@/components/Live2d'
export default {
  name: 'home',
  components: {
    HelloWorld,
    Live2d
  }
}
</script>
