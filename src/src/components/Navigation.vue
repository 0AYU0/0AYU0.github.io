<template>
  <div class="sticky">
    <header class="header">
      <a href="#about" class="nav-item">about</a>
      <a href="#experience" class="nav-item">experience</a>
      <a href="#projects" class="nav-item">projects</a>
      <a href="#contact" class="nav-item">contact</a>
    </header>
  </div>
</template>


<style>
.nav-item {
  color: black;
  font-size: 1.5rem;
  text-decoration: none;
}

.header {
  display: flex;
  flex-direction: row;
  font-family: DM Sans, sans-serif;
  justify-content: space-evenly;
}

.sticky {
  background: white;
  padding: 0.5rem;
  position: sticky;
  top: 0;
}
</style>
