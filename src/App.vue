<template>
  <div id="app" class="font-sans bg-primary h-full">
    <Navbar />
    <router-view
      class="md:px-8 pb-8 px-4 max-w-screen-xxl mx-auto min-h-screen"
    />
    <Footer />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';
import Footer from '@/components/Footer.vue';

export default {
  components: {
    Navbar,
    Footer
  }
};
</script>

<style>
html,
body {
  scroll-behavior: smooth;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
