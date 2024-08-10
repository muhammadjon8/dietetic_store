<script setup></script>

<template>
  <div class="py-9 container">
    <div class="flex items-center gap-5 justify-between">
      <nuxt-link to="/" class="flex items-center gap-3">
        <img src="/logo.png" alt="" class="w-9 h-14" />
        <h2 class="text-4xl font-bold text-primary">Organick</h2>
      </nuxt-link>
      <div class="flex gap-9">
        <nuxt-link to="/" class="text-primary text-[20px] font-bold"
          >Home</nuxt-link
        >
        <nuxt-link to="/" class="text-primary text-[20px] font-bold"
          >About</nuxt-link
        >
        <nuxt-link to="/" class="text-primary text-[20px] font-bold"
          >Pages</nuxt-link
        >
        <nuxt-link to="/" class="text-primary text-[20px] font-bold"
          >Shop</nuxt-link
        >
        <nuxt-link to="/" class="text-primary text-[20px] font-bold"
          >Projects</nuxt-link
        >
        <nuxt-link to="/" class="text-primary text-[20px] font-bold"
          >News</nuxt-link
        >
      </div>
      <div class="flex gap-3">
        <div class="flex bg-[#FAFAFA] items-center p-2 rounded-full w-[300px]">
          <input type="text" class="p-1 outline-none bg-[#FAFAFA] w-full" />
          <button class="bg-yashil rounded-full p-3 flex items-center">
            <Icon
              name="material-symbols:search"
              width="256"
              height="256"
              style="color: white"
            />
          </button>
        </div>
        <div
          class="flex border border-[#E0E0E0] rounded-full items-center gap-3 p-2"
        >
          <div class="flex items-center bg-primary p-3 rounded-full">
            <Icon
              name="mdi:cart-outline"
              width="256"
              height="256"
              style="color: white"
            />
          </div>
          <p class="text-xl font-semibold text-primary">Cart (0)</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
