<script setup>
import { ref } from "vue";
// TODO сделать перещелки и названия 2 столбцами чтоб ровненько было
import swi from "@/Components/smallThings/switch.vue";

const items = ref(["Здоровье", "Карьера", "Деньги", "Взаимоотношения"]);
</script>
<template>
    <div v-for="item in items" class="container flex align-items-center pb-5">
        <div class="mr=10 text-lg">{{ item }}</div>
        <swi class="ml-10"></swi>
    </div>
</template>
