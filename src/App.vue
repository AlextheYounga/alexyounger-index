<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <main class="w-full">
    <div class="vertical-center">
      <div class="w-3/4 flex mx-auto justify-between items-center">
        <header class="w-1/4 mr-12">
          <img alt="Vue logo" class="logo" src="@/assets/images/hammock-circle.png.webp" width="300" height="300" />
        </header>

        <div class="w-3/4">
          <RouterView />
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.vertical-center {
  margin: 0;
  position: absolute;
  top: 50%;
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
}
</style>
