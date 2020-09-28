<template>
  <div class="flex items-center justify-center h-screen bg-green-100">
    <div class="text-center">
      <img class="mx-auto" alt="Vue logo" src="./assets/logo.png" />
      <HelloWorld msg="Hello Vue 3.0 + Vite + Tailwindcss" />
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>
