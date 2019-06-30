<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <footersimpl/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import footersimpl from "@/components/footersimpl.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
