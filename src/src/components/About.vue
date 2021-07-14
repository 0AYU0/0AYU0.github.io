<template>
  <div id="about">
    <div class="intro-photo">
      <h1>about</h1>
      <img src="./../assets/AlexanderYu.jpg" class="photo"/>
    </div>
    <div class="background">
      hello!
      <div>
      my name is alex, and i'm a incoming second year student at the university of california, san diego pursuing a b.s. in computer science and a mathematics minor.
      </div>
    </div>
  </div>
</template>

<style>
#about {
  display: flex;
  font-family: DM Sans, sans-serif;
}

.background {
  display: flex;
  flex: 3;
  flex-direction: column;
  font-size: 1.25rem;
  margin-top: 2rem;
}

.intro-photo {
  display: flex;
  flex-direction: column;
  flex: 2;
  align-items: center;
}

.photo {
  width: 50%;
}
</style>