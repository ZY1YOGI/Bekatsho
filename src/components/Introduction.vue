<template>
  <h1 class="title">INTRODUCTION</h1>
  <h2 class="sub-title">The Concert Studio</h2>
  <img class="img" src="introduction.svg" alt="introduction" />
  <p class="paragraph">
    Eget mi proin sed libero enim sed faucibus turpis. Nisl rhoncus mattis
    rhoncus urna neque viverra justo. Vivamus at augue eget arcu dictum.
    Ultrices gravida dictum fusce ut placerat orci. Aenean et tortor at risus
    viverra adipisci ng at in. Mattis aliquam faucibus purus in massa. Est
    placerat in egestas erat imperdiet sed. Consequat sem per viverra nam libero
    justo laoreet sit amet. Aliquam etiam erat velit scelerisque in dictum non
    consectetur a. Laoreet sit amet cursus sit amet. Vel eros donec ac odio
    tempor orci dapibus. Sem nulla pharetra diam sit amet nisl suscipit
    adipiscing bibendum. Leo a diam sollicitudin tempor.
  </p>

  <button class="btn-get-started">Learn more about <span class="font-extrabold">'Bekatsho'</span></button>
</template>

<script setup lang="ts"></script>

<style scoped>
.title {
  @apply text-3xl text-white text-center mt-12 font-bold;
}
.sub-title {
  @apply text-xl text-white text-center py-3;
}

.img {
  @apply mx-auto;
}

.paragraph {
  @apply px-6 pt-6 text-white;
}

.btn-get-started {
  @apply py-3.5 px-10 rounded-3xl font-bold text-[#343045] mx-auto block mt-10;
  background: linear-gradient(90deg, #8176af 0%, #c0b7e8 100%);
}
</style>
