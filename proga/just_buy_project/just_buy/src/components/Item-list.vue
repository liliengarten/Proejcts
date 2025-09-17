<script setup>
    import ItemCard from './Item-card.vue';
</script>




<template>
    <!-- <div class="grid grid-cols-4 gap-5"> -->
    <div> 
      <ItemCard></ItemCard>
      <ItemCard></ItemCard>
      <ItemCard></ItemCard>
      <ItemCard></ItemCard>
      <ItemCard></ItemCard>
      <ItemCard></ItemCard>
      <ItemCard></ItemCard>
      <ItemCard></ItemCard>
    </div>
</template>

<style scoped>

  div {
    grid-template-columns: repeat(4);
  }

</style>