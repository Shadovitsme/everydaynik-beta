<script setup>
import {ref} from 'vue'
const props = defineProps({
  content: { type: String, required: true },
  link: {type: String, required :false},
})
</script>
<template>
       <div class="flex flex-wrap gap-6">
        <a class="relative" :href='props.link'>
        <span class="absolute top-0 left-0 mt-1 ml-1 h-full w-full rounded bg-black"></span>
        <span class="fold-bold relative inline-block h-full w-full rounded border-2 border-black bg-white px-3 py-1 text-base font-bold text-black transition duration-100 hover:bg-blue hover:text-gray">{{content}}</span>
    </a>
</div>
</template>