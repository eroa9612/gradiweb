<template>
  <div class="home">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Weather />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Weather from "../views/Weather";

export default {
  name: "Home",
  components: {
    Weather,
    // HelloWorld,
  },
};
</script>
