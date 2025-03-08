<template>
  <div id="app">
    <nav class="navbar">
      <div class="navbar-brand">
        <h1>Vue Demo</h1>
      </div>
      <div class="navbar-menu">
        <router-link to="/" class="navbar-item">Home</router-link>
        <router-link to="/about" class="navbar-item">About</router-link>
        <router-link to="/experts" class="navbar-item">Experts</router-link>
      </div>
    </nav>
    
    <main>
      <transition name="slide">
        <router-view />
      </transition>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
}

#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #0B0404FF;
  color: white;
  padding: 1rem 2rem;
}

.navbar-menu {
  display: flex;
  gap: 1rem;
}

.navbar-item {
  color: white;
  text-decoration: none;
  padding: 0.5rem 1rem;
  border-radius: 4px;
  transition: background-color 0.3s;
}

.navbar-item:hover {
  background-color: #2c3e50;
}

main {
  flex-grow: 1;
  display: flex;
  flex-direction: column;
}

.page-container {
  flex-grow: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 2rem;
  text-align: center;
}

.page-content {
  max-width: 800px;
  margin: 0 auto;
}

h1 {
  margin-bottom: 1rem;
}

p {
  line-height: 1.6;
}

.slide-enter-active, .slide-leave-active {
  transition: transform 0.5s ease;
}

.slide-enter-from, .slide-leave-to {
  transform: translateX(-100%);
}

.slide-enter-to, .slide-leave-from {
  transform: translateX(0);
}
</style>