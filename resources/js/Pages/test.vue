<script setup>
import sliders from '@/Components/smallThings/sliders.vue'
import swi from '@/Components/smallThings/switch.vue'
import lightButton from '@/Components/smallThings/buttons/lightButton.vue';
import InputError from '@/Components/maybeDelete/InputError.vue';
</script>
<template>
 
<!-- TODO сделать тут добавление этих элементов по затычке иммитирующей бд -->


    <sliders></sliders>
    <div class="flex pl-5">
    <lightButton content="сохранить"></lightButton>
    <lightButton content="сбросить"></lightButton>
</div>
</template>