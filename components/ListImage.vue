<template>
  <div>
  <section class="grid grid-cols-3 gap-4 w-1/6 mx-auto">
    <button class="rounded-md bg-orange-400 h-10 w-10" id="btn1" v-on:click="img = '1-200x100.jpg'"></button>
    <button class="rounded-md bg-orange-500 h-10 w-10" id="btn2" v-on:click="img = '2-200x100.jpg'"></button>
    <button class="rounded-md bg-orange-900 h-10 w-10" id="btn3" v-on:click="img = '3-200x100.jpg'"></button>
  </section>
    <div class="container mx-auto py-12">
      <img v-bind:src="require('~/assets/' +img)" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'ListImage',
  data() {
    return {
      img: '1-200x100.jpg'
    }
  },
  methods: {
  }
}
</script>
<style>

</style>
