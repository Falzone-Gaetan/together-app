<script setup>

</script>

<template>
<div class="inline-block bg-white border-none rounded-lg drop-shadow-xl dark:bg-gray-800 w-2/3">
    
    <a :href="route('details')">
        <img class=" rounded-t-lg  " src="../../../storage/app/public/asset/img/pexels-thirdman-5247203.jpg" alt="" />
    </a>
    <div class="p-6 ">
        <a :href="route('details')">
            <h5 class="pb-2 text-xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy</h5>
        </a>
        <p class="pb-3 font-normal text-gray-700 dark:text-gray-400">Here are the biggest </p>
        <a :href="route('details')" class="inline-flex items-center px-2 py-1 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
            Read more
            <svg aria-hidden="true" class="w-4 h-4 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
        </a>
    </div>
</div>
  </template>
  