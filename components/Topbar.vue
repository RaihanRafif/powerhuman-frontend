<template>
  <div class="pt-[50px] md:px-[50px] flex justify-between items-center px-4">
    <NuxtLink :to="{ name: 'index' }" class="nav-link">
      <img src="/assets/svgs/logo-type.svg" alt="">
    </NuxtLink>
    <a href="#" onclick="history.back()">
      <img src="/assets/svgs/ric-close-white.svg" alt="">
    </a>
  </div>
</template>
