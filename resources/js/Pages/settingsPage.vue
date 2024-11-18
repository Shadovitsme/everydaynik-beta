<script setup>
import { ref } from "vue";
import sliders from "@/Components/smallThings/sliders.vue";
import lightButton from "@/Components/smallThings/buttons/lightButton.vue";
import avatarIcon from "@/Components/smallThings/avatarIcon.vue";
import topMenu from "@/Components/blocks/topMenu.vue";
import sphereSwitch from "@/Components/blocks/sphereSwitch.vue";

</script>
<template>
    <topMenu></topMenu>


    <div class="mx-10">
        <div class="container flex align-items-center pb-5">
            <avatarIcon></avatarIcon>
            <h1 class="pl-4 text-2xl">Settings</h1>
        </div>
        <hr class="pb-4" />

        <div class="pb-10">
            <h1 class="text-xl pb-4">Life spheres</h1>
            <sphereSwitch></sphereSwitch>
        </div>

        <hr class="pb-4" />
        <div class="pb-10">
            <h1 class="text-lg">Spheres weight</h1>
            <sliders></sliders>
        </div>
        <div class="flex">
            <lightButton class="m-3" content="сохранить"></lightButton>
            <lightButton class="m-3" content="сбросить"></lightButton>
        </div>
    </div>
</template>
