<script setup>
import sliders from '@/Components/smallThings/sliders.vue'
import swi from '@/Components/smallThings/switch.vue'
import lightButton from '@/Components/smallThings/buttons/lightButton.vue';
import avatarIcon from '@/Components/smallThings/avatarIcon.vue';
</script>
<template>
 
<!-- TODO сделать тут добавление этих элементов по затычке иммитирующей бд -->

<div class="h-14 mb-8 mx-10 relative">
    <div class="text-4xl my-4 h-14 inline absolute left-0">EveryDaynik!</div>
    <div class="h-14 inline absolute right-0" >sjflsdjfkl</div>
</div>



<div class="mx-10">
    <!-- TODO вынести шапку в отдельный блок -->
    <div class="container flex align-items-center pb-5">
        <avatarIcon ></avatarIcon>
        <h1 class="pl-4 text-2xl ">Settings</h1>
    </div>
<hr class="pb-4">
<div class="pb-10">
<h1 class="text-lg pb-4">Life spheres</h1>
<swi class="pb-4"></swi>
</div>
<hr class="pb-4">
<div class="pb-10">
    <h1 class="text-lg">Spheres weight</h1>
    <sliders></sliders>
</div>
<div class="flex">
    <lightButton content="сохранить"></lightButton>
    <lightButton content="сбросить"></lightButton>
</div>
</div>
</template>