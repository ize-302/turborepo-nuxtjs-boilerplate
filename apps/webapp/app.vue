<script setup lang="ts">
const handleClick = () => {
	alert("Clicked Webapp button");
};
</script>

<template>
  <h1 class="text-3xl text-green-600 font-bold underline">
    Webapp
  </h1>
  <UButton @click="() => handleClick()">Click me</UButton>
</template>

