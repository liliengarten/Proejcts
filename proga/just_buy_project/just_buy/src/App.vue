<script setup>
  import Header from './components/Header.vue';
  import ItemList from './components/Item-list.vue';
</script>

<template>
  <Header></Header>

  <div class="max-w-[960px] mx-auto my-15">
    <h1 class="mb-10 text-[2rem] text-neutral-950"> Каталог товаров </h1>
    
    <ItemList></ItemList>
  </div>
</template>

<style scoped>
</style>
