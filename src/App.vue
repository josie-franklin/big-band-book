<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/test">Test</router-link>
  </nav>
  <router-view/>
</template>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

:root {
  --black: #1f1a17;
  --white: #fff;
  --gold: #ffbf00;
  --dark-gold: #cc7700;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--black);
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: var(--black);
}

nav a.router-link-exact-active {
  color: var(--dark-gold);
}
</style>
