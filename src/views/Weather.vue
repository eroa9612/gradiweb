<template>
  <div class="md:w-4/5 mx-auto h-screen rounded-md bg-gray-300">
    <div class="flex justify-end p-4">
      <img src="../assets/img/gradiweb.png" class="w-10 h-10" />
    </div>
    <div class="w-11/12 mx-auto bg-white rounded-3xl my-6">
      <Widget class="fixed md:mt-40 mt-20" />
      <div class="w-full py-10">
        <div
          class="absolute md:w-3/12 w-8/12 flex justify-center mt-16 md:mt-20"
        >
          <img :src="require(`../assets/icons/gps.svg`)" class="w-5 h-7 mr-2" />
          <span class="capitalize text-base font-extrabold text-purple-900"
            >bogotá</span
          >
        </div>
        <div class="flex justify-center">
          <img
            src="../assets/img/portada.jpg"
            class="w-11/12 md:h-72 rounded-3xl"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Widget from "../components/Widget";

export default {
  name: "Weather",
  components: {
    Widget,
    // HelloWorld,
  },
};
</script>

<style></style>
