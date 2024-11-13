<script setup>
import sliders from '@/Components/smallThings/sliders.vue'
import swi from '@/Components/smallThings/switch.vue'
import lightButton from '@/Components/smallThings/buttons/lightButton.vue';
import InputError from '@/Components/maybeDelete/InputError.vue';
</script>
<template>

<!-- TODO сделать тут добавление этих элементов по затычке иммитирующей бд -->
 <!-- TODO придумать как писать их в 2 столбца мол название сферы и результат. -->
<div class="block">
 <div class="inline-flex py-2">
   <p class="text-left pr-40 pl-5"> lsjflkasjdfl </p>
    <swi></swi>
</div>
</div>
<div class="block">
<div class="inline-flex py-2">
   <p class="text-left pr-40 pl-5"> lsjflkasjdfl </p>
    <swi></swi>
</div>
</div>

    <sliders></sliders>
    <div class="flex ">
    <lightButton content="сохранить"></lightButton>
    <lightButton content="сбросить"></lightButton>
</div>
</template>