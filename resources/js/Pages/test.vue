<script setup>
import sliders from '@/Components/smallThings/sliders.vue'
import swi from '@/Components/smallThings/switch.vue'
import lightButton from '@/Components/smallThings/buttons/lightButton.vue';
import InputError from '@/Components/maybeDelete/InputError.vue';
import avatarIcon from '@/Components/smallThings/avatarIcon.vue';
</script>
<template>
 
<!-- TODO сделать тут добавление этих элементов по затычке иммитирующей бд -->

<div class="w-full h-14 mb-8">
headplace
</div>

<div class="mx-10 h-dvh">
    <!-- TODO вынести шапку в отдельный блок -->
    <div class="container flex align-items-center pb-5">
        <avatarIcon ></avatarIcon>
        <h1 class="pl-4 text-2xl ">Settings</h1>
    </div>
<hr>
<h1 class="text-lg">Life spheres</h1>
</div>

<!-- <swi></swi>
    <sliders></sliders>
    <div class="flex pl-5">
    <lightButton content="сохранить"></lightButton>
    <lightButton content="сбросить"></lightButton>
</div> -->
</template>