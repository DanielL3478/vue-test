<template>
  <h1 :class="titleClass">Sign Up</h1>
  <div>
    <input type="text" placeholder="johndoe@gmail.com" />
    <input type="password" placeholder="qwerty123" />
    <button>Confirm</button>
  </div>
</template>

<script setup>
import { ref } from 'vue'
const titleClass = ref("title")
</script>

<style>
.title {
  color: aquamarine;
}
</style>