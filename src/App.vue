<!-- LOGICA -->
<script>
  export default {
    data() {
      return {
        message: 'Hello Node + Vite + Vue'
      }
    }
  }
</script>
<!-- DOM -->
<template>
  <div class="message">
    {{ message }}
  </div>
</template>
<!-- STILE -->
<style scoped>
.message {
  font-size: 64px;
  font-weight: bolder;
}
</style>
