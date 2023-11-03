<script>
  export default {
    name: 'AppHero',
    data() {
      return {
        test: "prova"
      }
    }
  }
</script>
<!-- DOM -->

<template>
  <div class="img-wrapper">
  <p>Ciao Jumbo!!!</p>
    <img src="../assets/834003.png" alt="jumbobg">
  </div>
</template>

<!-- STILE -->
<style scoped>
.img-wrapper {
    height: 600px;
    width: 100%;
    position: relative;
}

p {
  position: absolute;
  right: 5%;
}
img {
  display: block;
    width: 100%;
    height: 100%;
}

</style>