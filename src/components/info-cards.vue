<template>
  <div class="info-container">
    <div class="items">

      <div class="item item-phone">
        <img src="/icon/phone.svg" alt="location" />
        <div>
          <h1>Give Us a Call</h1>
          <h2>(+20) 010 0000 00 00</h2>
        </div>
      </div>

      <!-- <div class="item item-location">
        <img src="icon/location.svg" alt="location" />
        <div>
          <h1>Giza, engineers</h1>
          <h2>Egypt</h2>
        </div>
      </div>

      <div class="item item-mail">
        <img src="icon/mail.svg" alt="location" />
        <div>
          <h1>Send Us a Message</h1>
          <h2>Bekatsho@gmail.com</h2>
        </div>
      </div> -->
    </div>

    <button class="prev">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="30"
        height="30"
        viewBox="0 0 30 30"
        fill="none"
      >
        <path
          d="M17.5 21.25L11.25 15L17.5 8.75M3.75 15C3.75 21.2132 8.7868 26.25 15 26.25C21.2132 26.25 26.25 21.2132 26.25 15C26.25 8.7868 21.2132 3.75 15 3.75C8.7868 3.75 3.75 8.7868 3.75 15Z"
          stroke="white"
          stroke-width="1.5"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
    </button>
    <button class="next">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="30"
        height="30"
        viewBox="0 0 30 30"
        fill="none"
      >
        <path
          d="M12.5 21.25L18.75 15L12.5 8.75M26.25 15C26.25 21.2132 21.2132 26.25 15 26.25C8.7868 26.25 3.75 21.2132 3.75 15C3.75 8.7868 8.7868 3.75 15 3.75C21.2132 3.75 26.25 8.7868 26.25 15Z"
          stroke="white"
          stroke-width="1.5"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
    </button>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.info-container {
  @apply flex items-center justify-center rounded-full mt-12 mx-3 text-white relative py-3;
  background: radial-gradient(#3a3456f2, #211e2e);
  box-shadow: 0px 4px 4px 0px rgba(192, 183, 232, 0.01);
}

.prev {
  @apply absolute left-2 z-50;
}

.next {
  @apply absolute right-2 z-50;
}

.item {
  @apply flex items-center whitespace-nowrap justify-center space-x-1.5;
}

.item h1 {
  @apply font-bold;
}
</style>
