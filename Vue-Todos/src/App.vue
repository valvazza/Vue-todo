<script setup>
import {RouterView } from 'vue-router'
import TodoHeader from './components/TodoHeader.vue';
</script>

<template>
  <TodoHeader/>
  <RouterView />
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,300;0,600;1,800&display=swap');

* {
  font-family: "Nunito", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>