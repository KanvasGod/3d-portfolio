<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="hud-container">
    <div class="game-container">
      game screen
    </div>
    <div class="overlay">
      by
    </div>
  </div>
</template>



<style scoped>
.hud-container {
  position: relative;
}

.overlay {
  
}

.game-container {
  position: absolute;
  
  height: max-content;

}

</style>
