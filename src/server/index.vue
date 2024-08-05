<template>
  <div>
    index 页面
    <button @click="toAbout">ToAbout</button>
  </div>
</template>

<script setup>
function toAbout() {
  window.open("http://127.0.0.1:5173/about.html", "_blank");
}
</script>

<style scoped></style>
