<template>
  <div class="loader"></div>
</template>

<style scoped>
.loader {
  border: 1rem solid #f3f3f3;
  border-top: 1rem solid #3498db;
  border-radius: 50%;
  width: 5rem;
  height: 5rem;
  animation: spin 2s linear infinite;
}

@keyframes spin {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
</style>
