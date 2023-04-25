<script setup>

import AppLayout from '@/Layouts/AppLayout.vue';
import listCategories from '../Components/ListCategories.vue';
import ListNearbyActivity from '../Components/ListNearbyActivity.vue';
import ListNextActivity from '../Components/ListNextActivity.vue';

</script>

<template>
    <AppLayout title="Together">
        
        <template #header>
            <h2 class="font-semibold text-4xl text-zinc-100 leading-tight pb-9">
                Together
            </h2>
            <div class="flex justify-between items-center ">
            <label class="relative block basis-4/5 pr-2">
                <span class="sr-only">Search</span>
                <span class="absolute inset-y-0 left-0 flex items-center pl-2 ">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
                </svg>
                </span>
                <input class="placeholder:italic placeholder:text-slate-300 block placeholder:opacity-50  bg-cyan-700 border-none rounded-xl pl-9  w-full shadow-sm focus:outline-none focus:border-cyan-400 focus:ring-cyan-500 focus:ring-1 sm:text-sm " placeholder="Chercher des activités" type="text" name="search"/>
            </label>
            <a href="" ><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#ffffff" class="w-6 h-6">
                <path fill-rule="evenodd" d="M3.792 2.938A49.069 49.069 0 0112 2.25c2.797 0 5.54.236 8.209.688a1.857 1.857 0 011.541 1.836v1.044a3 3 0 01-.879 2.121l-6.182 6.182a1.5 1.5 0 00-.439 1.061v2.927a3 3 0 01-1.658 2.684l-1.757.878A.75.75 0 019.75 21v-5.818a1.5 1.5 0 00-.44-1.06L3.13 7.938a3 3 0 01-.879-2.121V4.774c0-.897.64-1.683 1.542-1.836z" clip-rule="evenodd" />
                </svg>
            </a>
            <a href="" ><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#ffffff" class="w-6 h-6">
            <path fill-rule="evenodd" d="M8.161 2.58a1.875 1.875 0 011.678 0l4.993 2.498c.106.052.23.052.336 0l3.869-1.935A1.875 1.875 0 0121.75 4.82v12.485c0 .71-.401 1.36-1.037 1.677l-4.875 2.437a1.875 1.875 0 01-1.676 0l-4.994-2.497a.375.375 0 00-.336 0l-3.868 1.935A1.875 1.875 0 012.25 19.18V6.695c0-.71.401-1.36 1.036-1.677l4.875-2.437zM9 6a.75.75 0 01.75.75V15a.75.75 0 01-1.5 0V6.75A.75.75 0 019 6zm6.75 3a.75.75 0 00-1.5 0v8.25a.75.75 0 001.5 0V9z" clip-rule="evenodd" />
            </svg>
            </a>
        </div>
        </template>
        
      <listCategories />   
      <ListNearbyActivity />
      <ListNextActivity/>
    </AppLayout>
</template>
