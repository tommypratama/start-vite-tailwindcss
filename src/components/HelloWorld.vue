<template>
  <h1 class="text-green-700 font-bold text-4xl mt-5">{{ msg }}</h1>
  <button
    class="bg-green-500 text-white font-semibold px-4 py-2 rounded-md mt-5"
    @click="count++"
  >count is: {{ count }}</button>
  <p class="mt-5">Edit <code>components/HelloWorld.vue</code> to test hot module replacement.</p>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
