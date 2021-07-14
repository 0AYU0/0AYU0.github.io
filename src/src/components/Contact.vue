<template>
  <div id="contact">
    <div class="contact-header">
      <h1>contact</h1>
    </div>
    <div class="contact-background">
      <a href="mailto:1alexander.yu@gmail.com" class="link-item">email: 1alexander.yu@gmail.com</a>  
      <div class="link-item">linkedin: <a href="https://www.linkedin.com/in/alexander-w-yu/">alexander-w-yu</a></div>
      <div class="link-item">github: <a href="https://github.com/0AYU0">0AYU0</a></div>
      <div class="link-item">goodreads: <a href="https://www.goodreads.com/alexander-yu">alexander-yu</a></div>
    </div>
  </div>
</template>

<style>
a {
  color: black;
  text-decoration: none;
}

#contact {
  display: flex;
  font-family: DM Sans, sans-serif;
}

.contact-background {
  display: flex;
  flex: 3;
  flex-direction: column;
  margin-top: 2rem;
}

.contact-header {
  display: flex;
  flex: 2;
  justify-content: center;
}

.link-item {
  margin-bottom: 0.5rem;
}
</style>