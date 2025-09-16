<template>
    <div class="item-card"> 
        <img class="item-picture" src="/product.png" alt="Item picture">

    <div class="item-card-description">
        <p class="text-neutral-950 text-[1.3rem]"> Jacket </p>
        <p class="text-[0.85rem] text-neutral-700 truncate mb-3"> Cool cool Cool lalalala sdfsdfds fsdfsdfdsfds </p>
        
        <div class="flex justify-between">
          <p class="text-[1.1rem] text-neutral-950"> 5400$ </p>

          <div class="add-to-card">
            <p class="text-[0.75rem] text-neutral-950"> В корзину </p>
          </div>
        </div>
      </div>
    </div>
</template>




<style scoped>
    .item-card {
        max-width: 90%;
        max-height: 90%;
        filter: drop-shadow(0px 0px 10px hsl(0, 0%, 30%));
        transition: all 1s;
    }

    .item-card:hover {
        transform: translate(0px, -5px);
        filter: drop-shadow(0px 0px 15px hsl(0, 0%, 30%));
        transition: all 1s;
    }

    .item-picture {
        padding: 10px;
        border-top-left-radius: 5px;
        border-top-right-radius: 5px;
        background-color: hsl(0, 0%, 93%);
    }

    .item-card-description {
        background-color: hsl(0, 0%, 95%);
        border-bottom-left-radius: 5px;
        border-bottom-right-radius: 5px;
        padding-inline: 10px;
        padding-top: 5px;
        padding-bottom: 8px;
    }

    .add-to-card {
        max-width: fit-content;
        max-height: fit-content;
        align-items: center;
        padding-inline: 15px;
        padding-block: 2px;
        border-radius: 5px;
        transition: all 1s;
        border: 1px solid transparent;
        background:
            linear-gradient(hsl(0, 0%, 99%)) padding-box,
            linear-gradient(to right, hsl(210, 70%, 70%), hsl(90, 70%, 83%));
        
    }

    .add-to-card:hover {
        transition: all 1s;
        border: 1px solid transparent;
        background:
            linear-gradient(to right, hsl(210, 70%, 70%), hsl(90, 70%, 83%)) padding-box,
            linear-gradient(hsl(0, 0%, 99%));
        
    }
</style>