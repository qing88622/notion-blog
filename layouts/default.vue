<template>
  <header
    class="bg-black/20 backdrop-blur-md py-4 px-6 flex justify-between items-center"
  >
    <a href="/" class="text-white text-lg font-bold hover:underline">
      qing's blog
    </a>
    <nav class="text-white space-x-4">
      <a href="#about" class="hover:underline">關於</a>
      <a href="#articles" class="hover:underline">文章列表</a>
      <a href="#categories" class="hover:underline">分類</a>
    </nav>
  </header>

  <slot />
</template>
<script lang="ts" setup></script>
