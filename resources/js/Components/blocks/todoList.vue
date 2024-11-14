<template>
    <div class="max-w-md mx-auto bg-white shadow-lg rounded-lg overflow-hidden mt-16">
    <div class="px-4 py-2">
        <h1 class="text-black font-bold text-2xl uppercase">To-Do List</h1>
    </div>
    <form class="w-full max-w-sm mx-auto px-4 py-2">
        <div class="flex items-center border-b-2 border-blue py-2">
            <input
                class="appearance-none bg-transparent border-none w-full text-gray-700 mr-3 py-1 px-2 leading-tight focus:outline-none"
                type="text" placeholder="Add a task">
            <button
                class="flex-shrink-0 bg-white hover:bg-blue border-gray hover:border-lightGray text-sm border-4 text-black py-1 px-2 rounded"
                type="button">
                Add
            </button>
        </div>
    </form>
    <ul class="divide-y divide-lightGray px-4">
        <li class="py-4">
            <!-- TODO добавить сюда переменные для того чтоб кол-во дел подтягиволось из бд и их названия и описания тоже-->
            <div class="flex items-center">
                <input id="todo1" name="todo1" type="checkbox"
                    class="h-4 w-4 text-blue focus:ring-lightGray border-gray rounded">
                <label for="todo1" class="ml-3 block text-black">
                    <span class="text-lg font-medium">Finish project proposal</span>
                    <span class="text-sm font-light text-gray">Due on 4/1/23</span>
                </label>
            </div>
        </li>
    </ul>
</div>
</template>