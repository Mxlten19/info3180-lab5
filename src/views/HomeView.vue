<template>
  <div class="container mt-5">
    <div class="text-center">
      <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
      <h1 class="mt-3">{{ message }}</h1>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";
let message = ref("Hello World! This is a VueJS and Flask Starter Template.")
</script>