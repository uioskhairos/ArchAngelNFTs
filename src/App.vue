<template>
  <nav>
    <!-- <router-link to="/">Home</router-link> -->
    <!-- <router-link to="/about">About</router-link> -->
  </nav>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #871edd;
  background-color: black;
}

nav {
  padding: 0px;
  background-color: black;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #9771d3;
}
</style>
