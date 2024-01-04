<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <h1>SITH | Game Dev</h1>

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/blog">Blog</RouterLink>
        <RouterLink to="/leaderboard">Leaderboard</RouterLink>
        <RouterLink to="/aboutus">About Us</RouterLink>
        <RouterLink to="/join">Join</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  z-index: 1;
  position: fixed;
  top: 0%;
  width: 100vw;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

.wrapper {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0 1rem 0 1rem;
  border-top-color: rgb(189, 0, 0);
  border-top-style: solid;
}

nav {
  font-size: 20px;
  text-align: center;
}
nav a.router-link-exact-active {
  color: var(--color-text);
}
nav a.router-link-exact-active:hover {
  background-color: transparent;
}
nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}
nav a:first-of-type {
  border: 0;
}
</style>
