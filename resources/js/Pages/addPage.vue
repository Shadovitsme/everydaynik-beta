<script setup>
import topMenu from "@/Components/blocks/topMenu.vue";
import lightButton from "@/Components/smallThings/buttons/lightButton.vue";
</script>

<template>
    <topMenu></topMenu>

    <div class="mx-10 h-10  flex align-items-center relative">
        <div class="inline text-2xl left-0 bottom-0 absolute">Add new task</div>
        <lightButton class="inline right-0 absolute " content="save"></lightButton>
    </div>
    <div class="mx-10 mt-10">
        <!-- TODO сделать в одну строку чтоб переключать можно было и сереньким -->
        <p class="inline pr-5">
            details
        </p>
        <p class="inline pr-5">
            parents and children
        </p>
        <p class="inline pr-5">
            weight
        </p>
    </div>
    <hr class="mx-10">
</template>
