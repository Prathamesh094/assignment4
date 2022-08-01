<template>
<nav class="mb-12 bg-indigo-300  text-black flex justify-end text-sm">
       <!-- <div class="px-72 pt-4"><img src="../hicare.png" alt="Logo" width="100" height="50"> </div> -->
        <ul class="pr-10 py-5 flex px space-x-11 ">
            <li class=" cursor-pointer hover:underline decoration-white-100"> Product Name </li>
            <li class=" cursor-pointer hover:underline decoration-white-500">Price </li>
            <li  class=" cursor-pointer hover:underline decoration-white-500"> Category </li>
            <li class="cursor-pointer  hover:underline decoration-white-500">Colors </li>   
            
        </ul>
    </nav>
  <div class="p-10 grid grid-cols-1 sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-5">
    <!--Card 1-->
    <div class="rounded overflow-hidden shadow-lg">
      <img  class="px-6" src="~/assets/shoes.jpg">
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2">Shoes</div>
        <p class="text-gray-700 text-base">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, Nonea! Maiores et perferendis eaque, exercitationem praesentium nihil.
        </p>
      </div>
   
    </div>
    <!--Card 2-->
    <div class="rounded overflow-hidden shadow-lg">
      <img class="px-6" src="~/assets/mensshirts.jpg">
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2">Shirst for men</div>
        <p class="text-gray-700 text-base">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, Nonea! Maiores et perferendis eaque, exercitationem praesentium nihil.
        </p>
      </div>
      
    </div>

    <!--Card 3-->
    <div class="rounded overflow-hidden shadow-lg">
      <img class="px-6" src="~/assets/kit.jpg">
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2">Kitchen appliences</div>
        <p class="text-gray-700 text-base">

          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, Nonea! Maiores et perferendis eaque, exercitationem praesentium nihil.
        </p>
      </div>
    </div>
  </div>
 
</template>