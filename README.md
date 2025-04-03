# Ecommerce-Project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="./output.css" rel="stylesheet">
    <title>Ecommerce-Website</title>
</head>
<body>
    <!--------------------------------main-navigation------------------------------------>    
    <div class="container p-5">
        <div class="md:flex md:flex-row md:justify-between mx-5 text-center">
            <div class="flex flex-row justify-center">
                <div class="bg-gradient-to-r from-purple-600 to bg-red-600 w-10 h-10 rounded-lg"></div>
                <h1 class=" text-3xl text-gray-600 ml-2">Logo</h1>
            </div>
            <div>
                <a href="#" class="text-gray-600 hover:text-purple-600 p-4">Home</a>
                <a href="#" class="text-gray-600 hover:text-purple-600 p-4">Shop</a>
                <a href="#" class="text-gray-600 hover:text-purple-600 p-4">Blog</a>
                <a href="#" class="text-gray-600 hover:text-purple-600 p-4">Contact</a>
                <a href="#" class="bg-purple-800 text-gray-50 hover:text-purple-600 px-3 py-2 rounded-full "><svg xmlns="http://www.w3.org/2000/svg" class=" h-6 w-6 inline-block" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
                  </svg>
                  Cart (0)
                </a>
            </div>
        </div>  
       
        <!---------------------Hero-section-------------------------------------------------->
       <div class="md:flex  md:flex-row mt-20 mx-5">
            <div class="md:w-2/5 flex flex-col justify-center items-center">
                <h2 class="font-serif text-5xl text-gray-600 mb-4 text-center md:self-start md:text-left">Some Catchy Title Here</h2>
                <p class="uppercase text-gray-600 tracking-wide text-center md:self-start md:text-left">Our brand tagline goes here.</p>
                <p class="uppercase text-gray-600 tracking-wide text-center md:self-start md:text-left">Our brand motto goes here.</p>
                <a href="#" class="bg-gradient-to-r from-red-600 to-pink-500 rounded-full py-4 px-8 text-gray-50 uppercase text-xl md:self-start my-3">Shop Now</a>
            </div>
            <img src="Images/product1.jpg"
            <div class="md:w-3/5">
                <img src="Images/product2.jpg"class="w-full">
            </div>
       </div> 

      <!---------------------Men's-section-------------------------------------->

        <div class="my-20 mx-5">
             <div class="flex flex-row justify-between">
                 <h2 class="text-3xl mb-2">Men's Collection Here</h2>
                 <a href="#" class="text-xl flex flex-row mb-2">View All<svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-5 ml-1" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"/>
                  </svg>
                  </a>
             </div>
             <div class="grid grid-flow-row lg:grid-cols-3 grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-10 my-4">
                <div class="shadow-lg rounded-lg">
                    <a href="#">
                        <img src="../Images/WhatsApp Image 2025-02-11 at 23.22.40_1fc4ec4c.jpg" class="rounded-tl-lg rounded-tr-lg">
                    </a>
                    <div class="p-5">
                        <h3>Men's T-Shirt</h3>
                        <div class="flex flex-row my-3">
                            <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"></div>
                        </div>
                        <div class="flex flex-row my-3">
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XL</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XXL</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">L</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">M</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">S</div>
                        </div>
                        <div class="flex flex-col xl:flex-row justify-between">
                            <a class="bg- bg-gradient-to-r from-red-600 to-pink-500 rounded-full py-2 px-4 text-gray-50 flex flex-row justify-center my-2  hover:from-pink-600 hover:to-pink-600 " href="#">
                                <svg xmlns="http://www.w3.org/2000/svg" class=" h-5 w-6 inline-block" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
                                </svg>
                              Add to Cart</a>
                              <a class="bg-purple-600 rounded-full py-2 px-4 text-gray-50 flex flex-row hover:bg-purple-700 justify-center my-2" href="#">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"/>
                                </svg>
                              View Datails</a>                           
                        </div>
                    </div>
                </div>
                <div class="shadow-lg rounded-lg">
                    <a href="#">
                        <img src="../Images/WhatsApp Image 2025-02-11 at 23.22.40_f50a7b39.jpg" class="rounded-tl-lg rounded-tr-lg">
                    </a>
                    <div class="p-5">
                        <h3> Towser</h3>
                        <div class="flex flex-row my-3">
                            <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"></div>
                        </div>
                        <div class="flex flex-row my-3">
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XL</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XXL</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">L</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">M</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">S</div>
                        </div>
                        <div class="flex flex-col xl:flex-row justify-between">
                            <a class=" bg-gradient-to-r from-red-600 to-pink-500 rounded-full py-2 px-4 text-gray-50 flex flex-row justify-center my-2 hover:from-pink-600 hover:to-pink-600 " href="#">
                                <svg xmlns="http://www.w3.org/2000/svg" class=" h-5 w-6 inline-block" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
                                </svg>
                              Add to Cart</a>
                              <a class="bg-purple-600 rounded-full py-2 px-4 text-gray-50 flex flex-row hover:bg-purple-700 justify-center my-2 " href="#">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"/>
                                </svg>
                              View Datails</a>                           
                        </div>
                    </div>
                </div>
                <div class="shadow-lg rounded-lg">
                    <a href="#">
                        <img src="../Images/WhatsApp Image 2025-02-11 at 23.22.39_0d9b2cc1.jpg" class="rounded-tl-lg rounded-tr-lg">
                    </a>
                    <div class="p-5">
                        <h3>Nike Shoes</h3>
                        <div class="flex flex-row my-3">
                            <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"></div>
                        </div>
                        <div class="flex flex-row my-3">
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XL</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XXL</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">L</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">M</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">S</div>
                        </div>
                        <div class="flex flex-col xl:flex-row justify-between">
                            <a class="bg- bg-gradient-to-r from-red-600 to-pink-500 rounded-full py-2 px-4 text-gray-50 flex flex-row justify-center my-2 hover:from-pink-600 hover:to-pink-600 " href="#">
                                <svg xmlns="http://www.w3.org/2000/svg" class=" h-5 w-6 inline-block" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
                                </svg>
                              Add to Cart</a>
                              <a class="bg-purple-600 rounded-full py-2 px-4 text-gray-50 flex flex-row hover:bg-purple-700 justify-center my-2" href="#">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"/>
                                </svg>
                              View Datails</a>                           
                        </div>
                    </div>
                </div>
                <div class="shadow-lg rounded-lg">
                    <a href="#">
                        <img src="../Images/WhatsApp Image 2025-02-11 at 23.22.39_38994c00.jpg" class="rounded-tl-lg rounded-tr-lg">
                    </a>
                    <div class="p-5">
                        <h3>Wirst Watch</h3>
                        <div class="flex flex-row my-3">
                            <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                            <div class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"></div>
                        </div>
                        <div class="flex flex-row my-3">
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XL</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XXL</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">L</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">M</div>
                            <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">S</div>
                        </div>
                        <div class="flex flex-col xl:flex-row justify-between">
                            <a class="bg- bg-gradient-to-r from-red-600 to-pink-500 rounded-full py-2 px-4 text-gray-50 flex flex-row justify-center my-2 hover:from-pink-600 hover:to-pink-600 " href="#">
                                <svg xmlns="http://www.w3.org/2000/svg" class=" h-5 w-6 inline-block" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
                                </svg>
                              Add to Cart</a>
                              <a class="bg-purple-600 rounded-full py-2 px-4 text-gray-50 flex flex-row hover:bg-purple-700 justify-center my-2" href="#">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"/>
                                </svg>
                              View Datails</a>                           
                        </div>
                    </div>
                </div>

             </div>
        </div>

   <!---------------------------------------Women's Collection-------------------------------------------------->
        
        <div class="my-20 mx-5">
            <div class="flex flex-row justify-between">
                <h2 class="text-3xl ">Women's Collection Here</h2>
                <a href="#" class="text-xl flex flex-row">View All<svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-5 ml-1" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                   <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"/>
                 </svg>
                 </a>
            </div>
            <div class="grid grid-flow-row lg:grid-cols-3 grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-10 my-4">
               <div class="shadow-lg rounded-lg">
                   <a href="#">
                       <img src="../Images/product1.jpg" class="rounded-tl-lg rounded-tr-lg">
                   </a>
                   <div class="p-5">
                       <h3>V Neck Tassel Cape</h3>
                       <div class="flex flex-row my-3">
                           <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"></div>
                       </div>
                       <div class="flex flex-row my-3">
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XL</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XXL</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">L</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">M</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">S</div>
                       </div>
                       <div class="flex flex-col xl:flex-row justify-between">
                           <a class="bg- bg-gradient-to-r from-red-600 to-pink-500 rounded-full py-2 px-4 text-gray-50 flex flex-row justify-center my-2  hover:from-pink-600 hover:to-pink-600 " href="#">
                               <svg xmlns="http://www.w3.org/2000/svg" class=" h-5 w-6 inline-block" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                               <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
                               </svg>
                             Add to Cart</a>
                             <a class="bg-purple-600 rounded-full py-2 px-4 text-gray-50 flex flex-row hover:bg-purple-700 justify-center my-2" href="#">
                               <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                   <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"/>
                               </svg>
                             View Datails</a>                           
                       </div>
                   </div>
               </div>
               <div class="shadow-lg rounded-lg">
                   <a href="#">
                       <img src="../Images/product2.jpg" class="rounded-tl-lg rounded-tr-lg">
                   </a>
                   <div class="p-5">
                       <h3>Printed Wrap Dress</h3>
                       <div class="flex flex-row my-3">
                           <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"></div>
                       </div>
                       <div class="flex flex-row my-3">
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XL</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XXL</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">L</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">M</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">S</div>
                       </div>
                       <div class="flex flex-col xl:flex-row justify-between">
                           <a class="bg- bg-gradient-to-r from-red-600 to-pink-500 rounded-full py-2 px-4 text-gray-50 flex flex-row justify-center my-2 hover:from-pink-600 hover:to-pink-600 " href="#">
                               <svg xmlns="http://www.w3.org/2000/svg" class=" h-5 w-6 inline-block" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                               <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
                               </svg>
                             Add to Cart</a>
                             <a class="bg-purple-600 rounded-full py-2 px-4 text-gray-50 flex flex-row hover:bg-purple-700 justify-center my-2 " href="#">
                               <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                   <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"/>
                               </svg>
                             View Datails</a>                           
                       </div>
                   </div>
               </div>
               <div class="shadow-lg rounded-lg">
                   <a href="#">
                       <img src="../Images/product3.jpg" class="rounded-tl-lg rounded-tr-lg">
                   </a>
                   <div class="p-5">
                       <h3>Blue Denim Dress</h3>
                       <div class="flex flex-row my-3">
                           <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"></div>
                       </div>
                       <div class="flex flex-row my-3">
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XL</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XXL</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">L</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">M</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">S</div>
                       </div>
                       <div class="flex flex-col xl:flex-row justify-between">
                           <a class="bg- bg-gradient-to-r from-red-600 to-pink-500 rounded-full py-2 px-4 text-gray-50 flex flex-row justify-center my-2 hover:from-pink-600 hover:to-pink-600 " href="#">
                               <svg xmlns="http://www.w3.org/2000/svg" class=" h-5 w-6 inline-block" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                               <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
                               </svg>
                             Add to Cart</a>
                             <a class="bg-purple-600 rounded-full py-2 px-4 text-gray-50 flex flex-row hover:bg-purple-700 justify-center my-2" href="#">
                               <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                   <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"/>
                               </svg>
                             View Datails</a>                           
                       </div>
                   </div>
               </div>
               <div class="shadow-lg rounded-lg">
                   <a href="#">
                       <img src="../Images/product4.jpg" class="rounded-tl-lg rounded-tr-lg">
                   </a>
                   <div class="p-5">
                       <h3>High Waist Denim Skirt</h3>
                       <div class="flex flex-row my-3">
                           <div class="bg-black h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-blue-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-white h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-red-800 h-5 w-5 rounded-full shadow-md mr-2"></div>
                           <div class="bg-green-700 h-5 w-5 rounded-full shadow-md mr-2"></div>
                       </div>
                       <div class="flex flex-row my-3">
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XL</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">XXL</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">L</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">M</div>
                           <div class="border-2 border-gray-300 text-gray-400 rounded-md text-xs px-2 py-1 mr-2">S</div>
                       </div>
                       <div class="flex flex-col xl:flex-row justify-between">
                           <a class="bg- bg-gradient-to-r from-red-600 to-pink-500 rounded-full py-2 px-4 text-gray-50 flex flex-row justify-center my-2 hover:from-pink-600 hover:to-pink-600 " href="#">
                               <svg xmlns="http://www.w3.org/2000/svg" class=" h-5 w-6 inline-block" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                               <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
                               </svg>
                             Add to Cart</a>
                             <a class="bg-purple-600 rounded-full py-2 px-4 text-gray-50 flex flex-row hover:bg-purple-700 justify-center my-2" href="#">
                               <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-4 mr-1" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                   <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"/>
                               </svg>
                             View Datails</a>                           
                       </div>
                   </div>
               </div>
            </div>
        </div>
        <!---------------------------Newsletter-section----------------------------------------------->
        <div class="rounded-lg shadow-lg my-20 flex flex-row mx-5">
            <div class="lg:w-3/5 w-full bg-gradient-to-r from-black to-purple-900 lg:from-black lg:via-purple-900 lg:to-transparent rounded-lg text-gray-100 p-12">
                <div class="lg:w-1/2">
                    <h3 class="text-2xl font-extrabold mb-4">Subscribe to get out offers first</h3>
                    <p class="mb-4 leading-relaxed">want to hear from us when we have new offers? sign up for our newsletter and we'll  email you every time we have new sale offers.</p>
                    <div>
                        <input type="email" placeholder="Enter email address" class="bg-gray-600 text-gray-100 placeholder-gray-400 px-2 py-3 w-full rounded-lg focus:outline-none">
                        <button type="submit"class=" bg-red-600 py-2 px-4 my-3 w-full rounded-lg">Subscribe</button>
                    </div>
                </div>
            </div>
            <div class="lg:w-2/5 w-full lg:flex lg:flex-row hidden">
                <img src="../Images/subscribe-banner.png"class="h-96">
            </div> 
        </div>
        
        <!----------------------------------------------footer-section-------------------------------------------------->
        <div class="border-t-2 border-gray-300 flex flex-col md:flex-row md:justify-between py-5 text-sm text-center mx-5">
            <div class="mb-4">
                <a href="#" class="mx-2.5">About</a>
                <a href="#" class="mx-2.5">Privacy Policy</a>
                <a href="#" class="mx-2.5">Terms of Services</a>
            </div> 
            <p>@copy : Copyright reserved 2024</p>
        </div> 

    </div>
</body>
</html>
