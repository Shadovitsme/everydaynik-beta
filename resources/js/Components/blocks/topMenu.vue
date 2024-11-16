<script setup>
import lightButton from "@/Components/smallThings/buttons/lightButton.vue";
import avatarIcon from "@/Components/smallThings/avatarIcon.vue";
</script>
<template>
    <div class="h-14 mb-8 mx-10 relative">
        <a href="/" class="text-4xl my-4 h-14 inline absolute left-0">
            EveryDaynik!
        </a>
        <div class="absolute bottom-0 right-0 content-end">
            <div class="container flex align-items-center">
                <lightButton
                    class="pr-4"
                    content="settings"
                    link="/settings"
                ></lightButton>
                <avatarIcon></avatarIcon>
            </div>
        </div>
    </div>
    <hr class="mx-10 bg-gray dark:bg-lightGray h-1 border-0 rounded">
</template>
