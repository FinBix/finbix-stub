<template>
  <div class="splash-container">
    <img src="@/assets/construction.png" alt="Splash Image" class="splash-image">
  </div>
</template>

<script>
export default {
  name: 'SplashImage'
}
</script>

<style scoped>
.splash-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.splash-image {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>
