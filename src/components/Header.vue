<script setup lang="ts">
import InfoCards from "./info-cards.vue";
</script>

<template>
  <header>
    <nav class="navigation">
      <div class="logo">
        <img src="/logo.svg" alt="Bekatsho" />
        <h1 class="title">Bekatsho</h1>
      </div>
      <button>
        <img src="/bars.svg" alt="bars" />
      </button>
    </nav>
  </header>
  <section class="hero">
    <img src="hero.svg" alt="hero" class="hero-img" />

    <div class="hero-container">
      <div class="hero-title">
        <span class="primary">Bekatsho</span> is always in <br />
        the <span class="primary">Happy Moments</span>
      </div>
      <button class="btn-get-started">Watch photo shoots</button>
    </div>

    <InfoCards />
  </section>
</template>

<style scoped>
.navigation {
  @apply flex justify-between px-[6%] py-6;
}

.logo {
  @apply flex items-center space-x-1.5;
}

.logo img {
  @apply w-16;
}

.title {
  @apply text-3xl font-bold;
  background: -webkit-linear-gradient(#c0b7e8, #8176af);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.hero-img {
  @apply -mt-16 relative -z-10;
}

.hero-container {
  @apply text-center space-y-6 -mt-40;
}

.hero-title {
  @apply text-3xl font-bold text-white;
}

.hero-title .primary {
  background: -webkit-linear-gradient(#c0b7e8, #8176af);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.btn-get-started {
  @apply py-3.5 px-10 rounded-3xl font-bold text-[#343045];
  background: linear-gradient(90deg, #8176af 0%, #c0b7e8 100%);
}
</style>
