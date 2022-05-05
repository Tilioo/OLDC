<template>
  <div class="grid grid-cols-3 gap-4 p-4 h-screen w-screen">
    <div class="bg-green-100 row-span-2 col-span-2"><MapFrame /></div>
    <div class="bg-green-100">View</div>
    <div class="bg-green-100">Edit</div>
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