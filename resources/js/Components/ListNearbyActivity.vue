<script setup>
import NearbyActivity from "./NearbyActivity.vue";

</script>
<template>
    <h2 class="font-semibold text-2xl text-zinc-100 leading-tight py-6 ml-2 "> Activités à proximité</h2>
    
    <div class="flex flex-nowrap gap-4 overflow-x-auto min-w-0 ml-2 items-center">
       <NearbyActivity class="flex-shrink-0"/>
       <NearbyActivity class="flex-shrink-0"/>
       <NearbyActivity class="flex-shrink-0"/>
       <NearbyActivity class="flex-shrink-0"/>
       <NearbyActivity class="flex-shrink-0"/>
       <NearbyActivity class="flex-shrink-0"/>
       <NearbyActivity class="flex-shrink-0"/>
       <button class="inline-flex items-center justify-center px-2 py-2 border border-transparent rounded-full font-medium text-white bg-white  hover:bg-opacity-20 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
  <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-2" viewBox="0 0 20 20" fill="eaeaea">
    <path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd" />
    <path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd" />
  </svg>
</button>

    </div>

</template>