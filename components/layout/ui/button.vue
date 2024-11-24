<template>
  <button
    class="btn bg-regular-1 rounded-10px font-circular h-58px text-17px px-27px"
  >
    {{ text }}
  </button>
</template>

<script setup>
const props = defineProps(["text"]);
</script>

<style>
</style>