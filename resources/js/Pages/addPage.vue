<script setup>
import topMenu from "@/Components/blocks/topMenu.vue";
import lightButton from "@/Components/smallThings/buttons/lightButton.vue";
import addPanel from "@/Components/addPanel.vue";
</script>

<template>
    <topMenu></topMenu>
    <div class="mx-10 h-10 mt-20 flex align-items-center relative">
        <div class="inline text-2xl left-0 bottom-0 absolute">Add new task</div>
        <lightButton class="inline right-0 absolute " content="save"></lightButton>
    </div>
    <div class="mt-10">
<addPanel></addPanel>
    </div>
    
</template>
