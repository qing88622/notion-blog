<template>
  <header
    class="bg-black/50 backdrop-blur-md py-4 px-6 flex justify-between items-center"
  >
    <a href="/" class="text-white text-lg font-bold hover:underline">
      qing blog
    </a>
    <nav class="text-white space-x-4">
      <a href="#about" class="hover:underline">關於</a>
      <a href="#articles" class="hover:underline">文章</a>
      <a href="#categories" class="hover:underline">分類</a>
    </nav>
  </header>

  <slot />
</template>
<script lang="ts" setup></script>
