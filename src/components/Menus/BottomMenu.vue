<template lang="">
  <footer class="fixed bottom-0 w-full z-50">
    <nav
      :class="{ hidden: hideIt }"
      class="md:hidden bg-purple-900
       [&>*]:text-white [&>*]:text-sm    
       flex justify-evenly items-center
       h-10"
    >
      <a href="#">Home 🏠</a>
      <a href="#my-works">Our Works 🖥️</a>
      <a href="#hire-us">Hire Us 🔈</a>
    </nav>
  </footer>
</template>
<script>
export default {
  props: ["hideIt"],
};
</script>
<style lang=""></style>
