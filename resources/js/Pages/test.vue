<script setup>
import sliders from '@/Components/sliders.vue'
import swi from '@/Components/switch.vue'
import lightButton from '@/Components/lightButton.vue';
</script>
<template>

<!-- TODO сделать тут добавление этих элементов по затычке иммитирующей бд -->
 <!-- TODO придумать как писать их в 2 столбца мол название сферы и результат. -->
    <swi></swi>
    <sliders></sliders>
    <div class="flex ">
    <lightButton content="сохранить"></lightButton>
    <lightButton content="сбросить"></lightButton>
</div>
</template>