<template>
  <div class="flex items-center justify-center text-center h-screen bg-green-100">
    <div>
      <div class="flex items-center justify-center">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-64"
          viewBox="0 0 48 48"
        >
          <path
            fill="#81c784"
            d="M23.987 17l-5.253-9H2.974l21.013 36L45 8H29.24z"
          />
          <path
            fill="#455a64"
            d="M29.24 8l-5.253 9-5.253-9h-7.588l12.841 22L36.828 8z"
          />
        </svg>
      </div>
      <HelloWorld msg="Hello Vue 3.0 + Vite + Tailwindcss v2" />
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
}
</script>
