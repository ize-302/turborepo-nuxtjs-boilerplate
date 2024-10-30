<script setup lang="ts">
const handleClick = () => {
	alert("Clicked Admin app button");
};
</script>

<template>
  <h1 class="text-3xl text-red-600 font-bold underline">
   Admin
  </h1>
  <UButton @click="() => handleClick()">Click me</UButton>
</template>
