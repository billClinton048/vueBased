<template>
  <div
    class="container my-10 flex max-w-7xl mx-auto justify-between items-center"
  >
    <div class=""><h1 class="text-orange-700 text-xl ml-5">Logo</h1></div>
    <div class="nav ">
      <ul class=" max-w-2xl flex justify-between  gap-20 items-center">
        <li><a href="#" class="text-orange-700 uppercase transition-all hover:text-orange-500" >Home</a></li>
        <li><a href="#" class="text-orange-700 uppercase transition-all hover:text-orange-500" >About</a></li>
        <li><a href="#" class="text-orange-700 uppercase transition-all hover:text-orange-500" >Contacts</a></li>
        <li><a href="#" class="text-orange-700 uppercase transition-all hover:text-orange-500" >Services</a></li>
      </ul>
    </div>
  
    <div class="btn ">
      <button class="text-lg rounded-3xl bg-orange-700 text-white px-5 hover:bg-orange-500 ">Get Started</button>
    </div>
    <div class="w-10 h-5 flex flex-col justify-between items-center sm:hidden">
      <div class="w-7 h-1 bg-orange-700"></div>
      <div class="w-7 h-1 bg-orange-700"></div>
      <div class="w-7 h-1 bg-orange-700"></div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
