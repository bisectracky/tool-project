<template>
    <header class="flex items-center justify-between p-4 bg-gray-100">
      <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
      <div class="wrapper">
        <nav class="flex space-x-4">
          <RouterLink to="/" class="text-blue-500 hover:text-blue-700">Home</RouterLink>
          <RouterLink to="/about" class="text-blue-500 hover:text-blue-700">About</RouterLink>
        </nav>
      </div>
      <span class="text-sm bg-red-300 py-1 px-3 rounded">June 2, 2024, Rainy</span>
    </header>
    <RouterView/>
  </template>
  
  <script>
  export default {
    name: 'AppHeader'
  }
  </script>
  
  <style scoped>
  .logo {
    width: 125px;
    height: 125px;
  }
  .wrapper {
    flex-grow: 1;
    display: flex;
    justify-content: center;
  }
  </style>
  