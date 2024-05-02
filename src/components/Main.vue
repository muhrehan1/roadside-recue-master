<script setup>
import Banner from './Banner.vue'
import About from './About.vue'
import Services from './Services.vue'
import Store from './Store.vue'
</script>

<template>
    <Banner />
    <About />
    <Services />
    <Store />

	<section class="secLoct" style="background-image: url('../../public/images/map.jpg');"></section>
</template>

<script>
  export default {
    name: 'Main',
  }
</script>