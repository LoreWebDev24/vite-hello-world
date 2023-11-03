<!-- LOGICA -->
<script>
// COMPONENTS IMPORT 
  import AppHero from "./components/AppHero.vue"
  // VUE
  export default {
    data() {
      return {
        title: 'La mia prima app con Vite!',
        message: 'Hello Node + Vite + Vue',
      }
    },
    components: {
      AppHero
    }
  }
</script>

<!-- DOM -->
<template>
  <div class="message">
    <h3>{{ title }}</h3>
    <p>{{ message }}</p>
    <AppHero/>
  </div>
</template>

<!-- STILE -->
<style scoped>
.message {
  font-size: 64px;
  font-weight: bolder;
}
</style>
