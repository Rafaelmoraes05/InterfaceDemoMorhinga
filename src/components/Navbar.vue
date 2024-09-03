<template>
    <nav class="navbar">
      <div class="navbar-title">Morhinga</div>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Navbar',
  }
  </script>
  
  <style scoped>
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #3f51b5; 
    color: white;
    padding: 10px 20px;
  }
  
  .navbar-title {
    font-size: 24px;
    font-weight: bold;
  }
  
  </style>
  