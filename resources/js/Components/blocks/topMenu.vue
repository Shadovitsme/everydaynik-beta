<script setup>
import lightButton from '@/Components/smallThings/buttons/lightButton.vue';
import avatarIcon from '@/Components/smallThings/avatarIcon.vue';
</script>
<template>
    <div class="h-14 mb-8 mx-10 relative">
    <div class="text-4xl my-4 h-14 inline absolute left-0">EveryDaynik!</div>
    <div class="absolute bottom-0 right-0 content-end">
        <div class="container flex align-items-center">
            <lightButton content="settings"></lightButton>
        <avatarIcon></avatarIcon>
    </div>
    </div>

</div>
</template>