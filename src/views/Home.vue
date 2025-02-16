<template>
  <div class="home">
    <h1>Welcome to My Vite Vue App</h1>
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from '../components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
.home {
  text-align: center;
  padding: 20px;
}
</style>