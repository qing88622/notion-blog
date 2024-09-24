<template>
  <div v-for="item in articles" class="bg-gray/20 p-5 rounded-md">
    <h2>{{ item.title }}</h2>
    <p>{{ item.date }}</p>
    <p>{{ item.text }}</p>
  </div>
</template>
<script lang="ts" setup>
const articles =[
    {
        title:"JavaScript - Promise 非同步物件使用方式及變體方法",
        date:"2021-08-08",
        category:"JavaScripts",
        text:"非同步處理一直以來都是 JavaScript 開發者很常遇到的情境，在之前，我們很常使用 callback 去完成任務，當結構變得複雜時，容易形成所謂的 callback hell，造成程式碼難以維護；在 ES6 版本中，新增了 Promise 物件，它能夠將非同步流程包裝成簡潔的結構，並提供統一的錯誤處理機制，解決了傳統 callback hell 的問題。此篇將會解析 Promise 的處理流程與相關方法。"
    },
    {
        title:"Promise 非同步物件使用方式及變體方法",
        date:"2021-08-08",
        category:"前端",
        text:"非同步處理一直以來都是 JavaScript 開發者很常遇到的情境，在之前，我們很常使用 callback 去完成任務，當結構變得複雜時，容易形成所謂的 callback hell，造成程式碼難以維護；在 ES6 版本中，新增了 Promise 物件，它能夠將非同步流程包裝成簡潔的結構，並提供統一的錯誤處理機制，解決了傳統 callback hell 的問題。此篇將會解析 Promise 的處理流程與相關方法。"
    },
    {
        title:"JavaScript - Promise 非同步物件使用方式及變體方法",
        date:"2021-08-08",
        category:"JavaScripts",
        text:"非同步處理一直以來都是 JavaScript 開發者很常遇到的情境，在之前，我們很常使用 callback 去完成任務，當結構變得複雜時，容易形成所謂的 callback hell，造成程式碼難以維護；在 ES6 版本中，新增了 Promise 物件，它能夠將非同步流程包裝成簡潔的結構，並提供統一的錯誤處理機制，解決了傳統 callback hell 的問題。此篇將會解析 Promise 的處理流程與相關方法。"
    },
    {
        title:"JavaScript - Promise 非同步物件使用方式及變體方法",
        date:"2021-08-08",
        category:"JavaScripts",
        text:"非同步處理一直以來都是 JavaScript 開發者很常遇到的情境，在之前，我們很常使用 callback 去完成任務，當結構變得複雜時，容易形成所謂的 callback hell，造成程式碼難以維護；在 ES6 版本中，新增了 Promise 物件，它能夠將非同步流程包裝成簡潔的結構，並提供統一的錯誤處理機制，解決了傳統 callback hell 的問題。此篇將會解析 Promise 的處理流程與相關方法。"
    },
] 
</script>