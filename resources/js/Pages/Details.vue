<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';


</script>
<template>
    <AppLayout title="Together">
    <div class=" font-sans leading-normal tracking-normal  from-teal-300 to-emerald-400 ">

    


<!-- Header avec l'image de l'activité -->
<header class="bg-cover bg-center h-96 pt-32 pb-16 relative" style="background-image: url('https:://picsum.photos/id/237/720/480')">
    <nav class="flex flex-row items-center justify-between bg-gray-600 p-2 absolute top-0 w-full bg-opacity-50">
 
 <a :href="route('dashboard')" class="text-white inline-block mx-2 py-2 px-4  basis-2/3">
<svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
 <path d="M15.41 7.41L14 6l-6 6 6 6 1.41-1.41L10.83 12l4.58-4.59z"/>
</svg>
</a>
 <button class="text-white inline-block rounded-full hover:bg-blue-700   ">
   <svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
     <path d="M19.25 3.272a2.034 2.034 0 0 0-2.863-.004l-9.982 9.75a.5.5 0 0 0-.147.346l-1.75 7a.5.5 0 0 0 .634.606l6.91-1.932a.5.5 0 0 0 .359-.36l9.75-9.982a2.03 2.03 0 0 0-.004-2.863zm-9.45 11.218l-5.517 1.542 1.542-5.516L14.342 6.3l3.757 3.757-7.304 7.304z"/>
   </svg>

 </button>
     <button class="text-white inline-block mr-2 rounded-full hover:bg-blue-700 ">
<svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
 <path d="M8 4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-8zm6 14H8V6h6v12z"/>
</svg>

</button>


</nav>
      <div class="absolute bottom-0 left-0 right-0 px-6">
        <h1 class="text-2xl font-bold text-white">Titre de l'activité</h1>
      </div>
    </header>
    <section class="">
        <div class="bg-teal-800 flex flex-raw items-center justify-between py-2">
            <h2 class="text-xl font-bold text-gray-200 mx-4">11 Novembre</h2>
            <div class="rounded-lg bg-slate-100 items-center px-2 mx-4 my-2 ">
                Randonnée
            </div>
        </div>

    </section>

    <!-- Section de description de l'activité -->
    <section class=" py-6 px-6">
      <h2 class="text-2xl font-bold text-gray-200 mb-2">Description</h2>
      <p class="text-gray-200 leading-normal">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus vulputate nunc et est aliquet pretium. Duis dictum velit et metus tincidunt, quis ultrices neque hendrerit. Fusce mattis nisl eget ante ultricies, eu bibendum massa laoreet.  </p>
    </section>

    <!-- Section de la carte Google Maps -->
    <section class="py-6 px-6">
      <h2 class="text-xl font-bold text-gray-200 mb-2">Localisation</h2>
      <div class="h-48">
        <!-- Ici, on peut intégrer la carte Google Maps -->
        <div class="bg-gray-500 text-white h-full flex items-center justify-center rounded-xl">Carte Google Maps</div>
      </div>
    </section>

    <section class=" px-4 py-6">
   
  <div class="flex flex-col items-start mb-4">
    <h2 class="text-xl font-bold text-gray-200 py-4">Organisé par</h2>
    <div class="w-12 h-12 bg-gray-300 rounded-full mr-4"></div>
    <div>
      <h3 class="text-lg font-medium text-gray-200 pt-4">Nom de l'auteur</h3>
      <p class="text-sm text-gray-200">Fonction de l'auteur</p>
    </div>
  </div>
 
</section>

<section class=" px-4 py-6">
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

<button class="bg-green-500 hover:bg-green-600 text-white font-bold py-1 px-6 rounded-2xl ml-4 mb-8">
  Inscription
</button>

</div>
</AppLayout>
</template>