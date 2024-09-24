<template>
  <header
    class="bg-black/20 backdrop-blur-md py-4 px-6 flex justify-between items-center"
  >
    <a href="/" class="text-white text-lg font-bold hover:underline">
      qing's blog
    </a>
    <nav class="text-white space-x-4 aa">
      <div v-for="item in nav" :key="item.href" :href="item.href" class="px-3">
        <a class="nav">{{ item.text }}</a>
      </div>
    </nav>
  </header>

  <slot />
</template>
<script lang="ts" setup>
const nav = [
  {
    text:"關於",
    href:"#about"
  },
  {
    text:"文章列表",
    href:"#about"
  },
  {
    text:"分類",
    href:"#about"
  },
]
</script>
<style>
.nav:hover{
  color: rgb(237, 226, 132);
  font-weight: 600;
  /* font-size: 1.1em; */
}
.aa{
  display:flex;
  justify-content: space-between;
}
</style>