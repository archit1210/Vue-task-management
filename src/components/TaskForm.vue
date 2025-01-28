<template>
    <form @submit.prevent="addTask">
      <label for="">Add your task  :     </label>
      <input type="text" placeholder="Enter a task" v-model="task" />
      <button type="submit">ADD</button>
    </form>
    <ul>
      <li v-for="(task, index) in tasks" :key="index">{{ task }}</li>
    </ul>
  </template>
  
  <script setup>
  import { ref } from 'vue';
  
  // Reactive variables
  const task = ref('');
  const tasks = ref([]);
  
  // Function to add task
  const addTask = () => {
    if (task.value.trim()) {
      tasks.value.push(task.value.trim());
      task.value = ''; // Clear input after adding
    }
  };
  </script>
  