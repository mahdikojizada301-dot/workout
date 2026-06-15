<template>
  <nav class="navbar">
    <div class="container">
      <h1 class="logo">MySite</h1>
      <ul class="nav-links">
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/contact">Contact</NuxtLink></li>
      </ul>
    </div>
  </nav>
</template>

<script setup>
// No extra logic needed unless you want dropdowns or dynamic links
</script>

<style scoped>
.navbar {
  background-color: #000000;
  padding: 1rem;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  color: #ecf0f1;
  font-size: 1.5rem;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1.5rem;
  margin: 0;
  padding: 0;
}

.nav-links a {
  color: #fffdfd;
  text-decoration: none;
  font-weight: 500;
}

.nav-links a:hover {
  text-decoration: underline;
}
</style>
