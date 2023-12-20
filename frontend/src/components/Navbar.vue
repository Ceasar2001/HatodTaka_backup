<!-- components/Navbar.vue -->
<template>
    <nav class="bg-gray-800 p-4 m-0 fixed w-full top-0">
      <div class="container mx-auto flex items-center justify-between">
        <!-- Logo or Brand -->
        <router-link to="/" class="text-white font-bold">Hatod Taka</router-link>
  
        <!-- Navigation Links -->
        <div class="space-x-4">
          <router-link to="/driver-info" class="text-white hover:text-gray-300">Profile</router-link>
          <!-- Add more navigation links as needed -->
        </div>
      </div>
    </nav>
  </template>
  
  <script setup>
  // You can add any logic or methods specific to the navbar component here
  </script>
  