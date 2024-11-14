<script setup>
import lightButton from '../smallThings/buttons/lightButton.vue';
</script>
<template>
    <div class=" mx-auto bg-white shadow-lg rounded-lg overflow-hidden mt-16 p-10">
    <div class="px-4 py-2 flex items-center relative pb-7">
        <h1 class="text-black font-bold text-2xl uppercase absolute left-0">To-Do List</h1>
        <lightButton class="absolute right-0" content="add"></lightButton>
    </div>

    <ul class="divide-y divide-lightGray px-4">
        <li class="py-4">
            <!-- TODO добавить сюда переменные для того чтоб кол-во дел подтягиволось из бд и их названия и описания тоже-->
            <div class="flex items-center">
                <input id="todo1" name="todo1" type="checkbox"
                    class="h-4 w-4 text-blue focus:ring-lightGray border-gray rounded">
                <label for="todo1" class="ml-3 block text-black">
                    <span class="text-lg font-medium pr-20">Finish project proposal</span>
                    <span class="text-sm font-light text-gray">Due on 4/1/23</span>
                </label>
            </div>
        </li>
    </ul>
</div>
</template>