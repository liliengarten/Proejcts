<template>
  <header class="flex items-center bg-white h-[69px] shadow-md">
    <div class="flex items-center justify-between max-w-[960px] w-full mx-auto ">
      <div class="h-[48px]">
        <img src="/logo.svg" alt="logo" class="h-full w-auto object-contain">
      </div>
      
      <nav>
        <ul class="flex gap-3">
          <li class="h-6 flex gap-2">
            <img src="/cart.svg" alt="" class="h-full w-auto object-contain">
            <p class="hover:text-blue-500"> Корзина </p> 
          </li>
          
          <li class="h-6 flex gap-2">
            <img src="/user.svg" alt="" class="h-full w-auto object-contain">
            <p class="hover:text-blue-500"> Профиль </p>
          </li>  
        </ul>
      </nav>
    </div>
  </header>
</template>