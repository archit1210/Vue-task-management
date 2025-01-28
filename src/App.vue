<template>
  <Navbar/>
  <TaskForm/>
  <h1>This is app component</h1>
</template>
<script setup>
import Navbar from './components/Navbar.vue';
import TaskForm from './components/TaskForm.vue';
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Figtree:ital,wght@0,300..900;1,300..900&display=swap');
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body{
  font-family: "Figtree", serif;;
}
</style>

