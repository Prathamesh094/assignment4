<template>
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
</template>

<script>
export default{
    data(){
        return{
            products:[]
            product:{
                productName:'',
                price:'',
                category:'',
                color:''

            }
        }
    }
    
}
</script>