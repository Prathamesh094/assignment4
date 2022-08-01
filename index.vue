<template>
<nav class="mb-12 bg-indigo-300  text-black flex justify-end text-sm">
       <!-- <div class="px-72 pt-4"><img src="../hicare.png" alt="Logo" width="100" height="50"> </div> -->
        <ul class="pr-10 py-5 flex px space-x-11 ">
            <li class=" cursor-pointer hover:underline decoration-white-100"> Product Name </li>
            <li class=" cursor-pointer hover:underline decoration-white-500">price </li>
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
        <table class=" place-content-center table-fixed  border border-spacing-3.5 border-separate align-top">
        <div v-for="item in products">
       <tr>
        <th>{{productName}}</th>
        <th>{{price}}</th>
        <th>{{color}}</th>
        </tr>
        </div>
         <th>productName</th>
        <th>price</th>
        <th>color</th>
        
        <tbody>
        
        <tr>
        <th>{{productName}}</th>
        <th>{{price}}</th>
        <th>{{color}}</th>
        </tr>

        
        </tbody>
        </table>
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
    <div>
    <form class="px-4 my-32 max-w-3xl max-auto space-y-2 place-content-center" onsubmit="onFormSubmit()" autocomplete="off">
                    <h1 class="text-3xl semibold">Enter Product details</h1>
                    <p class="text-1xl  text-gray-500 py-1">Product that you add will be visible to other.</p>
                
                    <div>
                        <label>Product Name    :</label>
                        <input class="border-gray-400 block py-1 px-4 w-52 rounded focus :outline-none focus:border-cyan-600" type="text" name="Fname" id="Fname">
                    </div>
                    <div>
                        <label>Price    :</label>
                        <input class="border-gray-400 block py-1 px-4 w-52 rounded focus :outline-none focus:border-cyan-600" type="text" name="Lname" id="Lname">
                    </div>

                    <div>
                        <label>Category     :</label>
                        <input class="border-gray-400 block py-1 px-4 w-52 rounded focus :outline-none" type="text" name="add" id="add">
                    </div>
                    <div>
                        <label>Colors  :</label>
                        <input class="border-gray-400 block py-1 px-4 w-52 rounded focus :outline-none" type="text" name="cn" id="cn">
                    </div>
                    
                    <div class="form-action-buttons">
                        <input type="submit" class="bg-green-200 px-4 py-1 rounded" value="Submit">
            
                    </div>
                
                </form>
    </div>
  </div>
 
</template>

<script>
export default{
    data(){
        return{
            products:[],
            newproduct:{
                productName:'',
                price:'',
                color:''

            }
        }
    }
    
}
</script>