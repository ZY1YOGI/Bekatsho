<template>
  <footer>
    <img src="/footer.svg" alt="footer" class="mx-auto" />
    <h1 class="title">SOCIALIZE WITH HYDRA</h1>

    <div class="social">
      <button><img src="/icon/social/facebook.svg" alt="facebook" /></button>
      <button><img src="/icon/social/twitter.svg" alt="twitter" /></button>
      <button><img src="/icon/social/linkedin.svg" alt="linkedin" /></button>
      <button><img src="/icon/social/youtube.svg" alt="youtube" /></button>
      <button><img src="/icon/social/instagram.svg" alt="instagram" /></button>
      <button><img src="/icon/social/pinterest.svg" alt="pinterest" /></button>
    </div>
    <button class="btn-get-started">
      Learn more about <span class="font-extrabold">'Bekatsho'</span>
    </button>

    <img src="/icon/line.svg" alt="line" class="line" />

    <p class="rights-reserved">
      2023 © Bekatsho LANDING PAGE <br />
      BY Youssef Amjad <br />
      ALL RIGHTS RESERVED
    </p>
  </footer>
</template>

<script setup lang="ts"></script>

<style scoped>
.title {
  @apply text-white text-xl text-center font-semibold mt-6;
}

.social {
  @apply flex items-center justify-center space-x-6 mt-6;
}

.btn-get-started {
  @apply py-3.5 px-10 rounded-3xl font-bold text-[#343045] block mx-auto mt-12;
  background: linear-gradient(90deg, #8176af 0%, #c0b7e8 100%);
}

.line {
  @apply mx-auto mt-12;
}

.rights-reserved {
  @apply text-white text-2xl text-center mt-8 my-12 font-semibold px-1;
}
</style>
