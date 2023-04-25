<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';


</script>
<template>
<AppLayout>
    <div class=" font-sans leading-normal tracking-normal  from-teal-300 to-emerald-400 ">

    


<!-- Header avec l'image de l'activité -->

<nav class="flex flex-row items-center justify-between bg-gray-600 p-2  w-full bg-opacity-50">
 
 <a :href="route('dashboard')" class="text-white inline-block mx-2 py-2 px-4  basis-2/3">
<svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
 <path d="M15.41 7.41L14 6l-6 6 6 6 1.41-1.41L10.83 12l4.58-4.59z"/>
</svg>
</a>

     <button class="text-white inline-block mr-2 rounded-full  ">
<svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
 <path d="M8 4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-8zm6 14H8V6h6v12z"/>
</svg>

</button>


</nav>

<section class="ml-4  py-6">
   
   <div class="flex flex-col items-start mb-4">
     
     <div class="w-12 h-12 bg-gray-300 rounded-full mr-4"></div>
     <div>
       <h3 class="text-lg font-medium text-gray-200 pt-4">Nom de l'auteur</h3>
       <p class="text-sm text-gray-200">Fonction de l'auteur</p>
     </div>
   </div>
  
 </section>
     

    <!-- Section de description de l'activité -->
    <section class=" py-6 ml-4">
      <h2 class="text-2xl font-bold text-gray-200 mb-2">Description</h2>
      <p class="text-gray-200 leading-normal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus vulputate nunc et est aliquet pretium. Duis dictum velit et metus tincidunt, quis ultrices neque hendrerit. Fusce mattis nisl eget ante ultricies, eu bibendum massa laoreet.  </p>
    </section>


   

<section class=" ml-4 py-6">
<div class="py-4 ">
    <h3 class="text-lg  text-gray-200 font-bold mb-2">Nombre de participants</h3>
    <div class="grid grid-cols-6 gap-1 my-4">
        <img class="w-10 h-10  rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 1">
        <img class="w-10 h-10  rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 2">
        <img class="w-10 h-10 rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 3">
        <img class="w-10 h-10  rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 4">
        <img class="w-10 h-10  rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 5">
        <img class="w-10 h-10  rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 2">
        <img class="w-10 h-10  rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 3">
        <img class="w-10 h-10 rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 4">
        <img class="w-10 h-10  rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 5">
        <img class="w-10 h-10  rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 2">
        <img class="w-10 h-10  rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 3">
        <img class="w-10 h-10  rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 4">
        <img class="w-10 h-10 rounded-full object-cover mr-2" src="https://via.placeholder.com/150" alt="Participant 5">
    </div>
</div>
</section>



</div>
</AppLayout>
</template>