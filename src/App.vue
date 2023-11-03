<!-- LOGICA -->
<script>
// COMPONENTS IMPORT 
  import componentJumbo from "./components/AppHero.vue"
  // VUE
  export default {
    data() {
      return {
        title: 'La mia prima app con Vite!',
        message: 'Hello Node + Vite + Vue',
        components: {
          componentJumbo: componentJumbo
        }
      }
    }
  }
</script>

<!-- DOM -->
<template>
  <div class="message">
    <componentJumbo></componentJumbo>
    <h3>{{ title }}</h3>
    <p>{{ message }}</p>
  </div>
</template>

<!-- STILE -->
<style scoped>
.message {
  font-size: 64px;
  font-weight: bolder;
}
</style>
