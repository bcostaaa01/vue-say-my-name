<script setup>
import { ref } from 'vue'

const myName = ref("")

function sayName () {
  myName.value = "Bruno"
}
</script>

<template>
  

  <img src="https://i.pinimg.com/originals/e4/26/70/e426702edf874b181aced1e2fa5c6cde.gif" alt="">

  <div class="card">
    <button type="button" @click="sayName">My name is {{ myName }}</button>
    </div>
    </template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
