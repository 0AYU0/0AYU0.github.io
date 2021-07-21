<template>
  <div id="contact">
    <div class="contact-header">
      <h1><mark>contact</mark></h1>
    </div>
    <div class="contact-background">
      <div class="main-links">
        <div class="col">
          <div class="link-item"><a href="mailto:1alexander.yu@gmail.com">email: <br/> 1alexander.yu@gmail.com</a></div> 
          <div class="link-item">linkedin: <br/> <a href="https://www.linkedin.com/in/alexander-w-yu/">alexander-w-yu</a></div>
        </div>
        <div class="col">
          <div class="link-item">github: <br/> <a href="https://github.com/0AYU0">0AYU0</a></div>
          <div class="link-item">medium: <br/> <a href="https://medium.com/@TheAYU_">TheAYU_</a></div>
        </div>
        </div>
      other links!
      <div class="main-links">
        <div class="col">
          <div class="link-item"> goodreads: <br/><a href="https://www.goodreads.com/alexander-yu">alexander-yu</a></div>
        </div>
            <div class="col">
          <div class="link-item"> lichess: <br/><a href="https://lichess.org/@/TheAYU">TheAYU</a></div>
        </div>
      </div>
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

.col {
  flex: 1;
}

.contact-background {
  display: flex;
  flex: 3;
  flex-direction: column;
  font-size: 1.25rem;
}

.contact-header {
  display: flex;
  flex: 2;
  justify-content: center;
}

.link-item {
  margin: 1rem 0;
}

.main-links {
  display: flex;
  flex-direction: row;

}
</style>