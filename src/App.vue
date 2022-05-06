<template>
  <div class="bg-gradient-to-r from-gray-700 via-gray-900 to-black ">
    <div class="grid grid-cols-3 gap-4 p-4 h-screen w-screen">
      <div class="bg-gray-400 col-span-3 rounded-lg m-3">Head</div>
      <div class="row-span-6 col-span-2 m-3"><MapFrame /></div>
      <div class="row-span-3 bg-gray-400 rounded-lg m-3">View</div>
      <div class="row-span-3 bg-gray-400 rounded-lg m-3">Edit</div>
    </div>
  </div>
</template>

<script>
import MapFrame from "./components/MapFrame.vue";

export default {
  name: "App",
  components: {
    MapFrame,
  },
};
</script>