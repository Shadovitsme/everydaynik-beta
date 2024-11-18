<script setup>
import {ref} from 'vue'
const props = defineProps({
  content: { type: String, required: true },
  link: {type: String, required :false},
})
</script>
<template>
       <div class="flex flex-wrap justify-center gap-6">
        <a class="relative" :href='props.link'>
        <span class="absolute top-0 left-0 mt-1 ml-1 h-full w-full rounded bg-gray"></span>
        <span class="fold-bold relative inline-block h-full w-full rounded border-2 border-black bg-black px-3 py-1 text-base font-bold text-white transition duration-100 hover:bg-gray hover:text-blue">{{content}}</span> 
    </a>
    </div>
</template>