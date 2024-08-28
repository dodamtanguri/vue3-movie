<template>
  <nav class="navbar">
    <a  href="#">HOME</a>
    <a href="#">MOVIES</a>
    <a href="#">ABOUT</a>
  </nav>
</template>


<script>
  export default {
    name: "NavbarComponent",

  }
</script>


<style>
  .navbar {
    background: #000;
    padding: 20px;
    text-align: center;
  }
  .navbar a {
    color: #fff;
    text-decoration: none;
    padding: 1rem 1rem;
  }
</style>