<script setup>
import sliders from '@/Components/sliders.vue'
import swi from '@/Components/switch.vue'
import lightButton from '@/Components/lightButton.vue';
</script>
<template>

<lightButton></lightButton>

<!-- TODO сделать тут добавление этих элементов по затычке иммитирующей бд -->
 <!-- TODO придумать как писать их в 2 столбца мол название сферы и результат. -->
    <swi></swi>
    <sliders></sliders>





<img class="w-10 h-10 p-1 rounded-full ring-2 ring-gray-300 dark:ring-gray-500" src="/docs/images/people/profile-picture-5.jpg" alt="Bordered avatar">

<button class="bg-gray-600 rounded-full w-48 h-16 text-white font-semibold">
    <div class="flex gap-3 justify-center items-center">
      <span>
          <svg class="w-8 h-8" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" >
           <path stroke-linecap="round" stroke-linejoin="round" d="M10.5 6h9.75M10.5 6a1.5 1.5 0 11-3 0m3 0a1.5 1.5 0 10-3 0M3.75 6H7.5m3 12h9.75m-9.75 0a1.5 1.5 0 01-3 0m3 0a1.5 1.5 0 00-3 0m-3.75 0H7.5m9-6h3.75m-3.75 0a1.5 1.5 0 01-3 0m3 0a1.5 1.5 0 00-3 0m-9.75 0h9.75" />
          </svg>
      </span>
      <span class="text-xl">Settings</span>
    </div>
</button>

<ul class="bg-white shadow overflow-hidden sm:rounded-md max-w-sm mx-auto mt-16">
    <li>
        <div class="px-4 py-5 sm:px-6">
            <div class="flex items-center justify-between">
                <h3 class="text-lg leading-6 font-medium text-gray-900">Item 1</h3>
                <p class="mt-1 max-w-2xl text-sm text-gray-500">Description for Item 1</p>
            </div>
            <div class="mt-4 flex items-center justify-between">
                <p class="text-sm font-medium text-gray-500">Status: <span class="text-green-600">Active</span></p>
                <a href="#" class="font-medium text-indigo-600 hover:text-indigo-500">Edit</a>
            </div>
        </div>
    </li>
    <li class="border-t border-gray-200">
        <div class="px-4 py-5 sm:px-6">
            <div class="flex items-center justify-between">
                <h3 class="text-lg leading-6 font-medium text-gray-900">Item 2</h3>
                <p class="mt-1 max-w-2xl text-sm text-gray-500">Description for Item 2</p>
            </div>
            <div class="mt-4 flex items-center justify-between">
                <p class="text-sm font-medium text-gray-500">Status: <span class="text-red-600">Inactive</span></p>
                <a href="#" class="font-medium text-indigo-600 hover:text-indigo-500">Edit</a>
            </div>
        </div>
    </li>
    <li class="border-t border-gray-200">
        <div class="px-4 py-5 sm:px-6">
            <div class="flex items-center justify-between">
                <h3 class="text-lg leading-6 font-medium text-gray-900">Item 3</h3>
                <p class="mt-1 max-w-2xl text-sm text-gray-500">Description for Item 3</p>
            </div>
            <div class="mt-4 flex items-center justify-between">
                <p class="text-sm font-medium text-gray-500">Status: <span class="text-yellow-600">Pending</span></p>
                <a href="#" class="font-medium text-indigo-600 hover:text-indigo-500">Edit</a>
            </div>
        </div>
    </li>
</ul>

<div class="p-12 dark:bg-gray-800">
    <h5 class="text-slate-900 font-semibold mb-4 text-sm leading-6 dark:text-slate-100">On this page</h5>
    <ul class="text-slate-700 text-sm leading-6">
        <li>
            <a href="#class-reference"
                class="block py-1 font-medium hover:text-slate-900 dark:text-slate-400 dark:hover:text-slate-300">Quick
                reference
            </a>
        </li>
        <li>
            <a href="#basic-usage" class="block py-1 font-medium font-medium text-sky-500 dark:text-sky-400">Basic
                usage
            </a>
        </li>
        <li class="ml-4">
            <a href="#adding-an-outer-shadow" class="group flex items-start py-1 text-sky-500 dark:text-sky-400">
                <svg width="3" height="24" viewBox="0 -9 3 24"
                    class="mr-2 text-slate-400 overflow-visible group-hover:text-slate-600 dark:text-slate-600 dark:group-hover:text-slate-500">
                    <path d="M0 0L3 3L0 6" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round">
                    </path>
                </svg>Adding an outer shadow
            </a>
        </li>
        <li class="ml-4">
            <a href="#adding-an-inner-shadow"
                class="group flex items-start py-1 hover:text-slate-900 dark:text-slate-400 dark:hover:text-slate-300">
                <svg width="3" height="24" viewBox="0 -9 3 24"
                    class="mr-2 text-slate-400 overflow-visible group-hover:text-slate-600 dark:text-slate-600 dark:group-hover:text-slate-500">
                    <path d="M0 0L3 3L0 6" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round">
                    </path>
                </svg>Adding an inner shadow
            </a>
        </li>
        <li class="ml-4">
            <a href="#removing-the-shadow"
                class="group flex items-start py-1 hover:text-slate-900 dark:text-slate-400 dark:hover:text-slate-300">
                <svg width="3" height="24" viewBox="0 -9 3 24"
                    class="mr-2 text-slate-400 overflow-visible group-hover:text-slate-600 dark:text-slate-600 dark:group-hover:text-slate-500">
                    <path d="M0 0L3 3L0 6" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round">
                    </path>
                </svg>Removing the shadow
            </a>
        </li>
        <li>
            <a href="#applying-conditionally"
                class="block py-1 font-medium hover:text-slate-900 dark:text-slate-400 dark:hover:text-slate-300">Applying
                conditionally
            </a>
        </li>
        <li class="ml-4">
            <a href="#hover-focus-and-other-states"
                class="group flex items-start py-1 hover:text-slate-900 dark:text-slate-400 dark:hover:text-slate-300">
                <svg width="3" height="24" viewBox="0 -9 3 24"
                    class="mr-2 text-slate-400 overflow-visible group-hover:text-slate-600 dark:text-slate-600 dark:group-hover:text-slate-500">
                    <path d="M0 0L3 3L0 6" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round">
                    </path>
                </svg>Hover, focus, and other states
            </a>
        </li>
        <li class="ml-4">
            <a href="#breakpoints-and-media-queries"
                class="group flex items-start py-1 hover:text-slate-900 dark:text-slate-400 dark:hover:text-slate-300">
                <svg width="3" height="24" viewBox="0 -9 3 24"
                    class="mr-2 text-slate-400 overflow-visible group-hover:text-slate-600 dark:text-slate-600 dark:group-hover:text-slate-500">
                    <path d="M0 0L3 3L0 6" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round">
                    </path>
                </svg>Breakpoints and media queries
            </a>
        </li>
        <li>
            <a href="#using-custom-values"
                class="block py-1 font-medium hover:text-slate-900 dark:text-slate-400 dark:hover:text-slate-300">Using
                custom values
            </a>
        </li>
        <li class="ml-4">
            <a href="#customizing-your-theme"
                class="group flex items-start py-1 hover:text-slate-900 dark:text-slate-400 dark:hover:text-slate-300">
                <svg width="3" height="24" viewBox="0 -9 3 24"
                    class="mr-2 text-slate-400 overflow-visible group-hover:text-slate-600 dark:text-slate-600 dark:group-hover:text-slate-500">
                    <path d="M0 0L3 3L0 6" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round">
                    </path>
                </svg>Customizing your theme
            </a>
        </li>
        <li class="ml-4">
            <a href="#arbitrary-values"
                class="group flex items-start py-1 hover:text-slate-900 dark:text-slate-400 dark:hover:text-slate-300">
                <svg width="3" height="24" viewBox="0 -9 3 24"
                    class="mr-2 text-slate-400 overflow-visible group-hover:text-slate-600 dark:text-slate-600 dark:group-hover:text-slate-500">
                    <path d="M0 0L3 3L0 6" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round">
                    </path>
                </svg>Arbitrary values
            </a>
        </li>
    </ul>
</div>

<div class="max-w-md mx-auto bg-white shadow-lg rounded-lg overflow-hidden mt-16">
    <div class="px-4 py-2">
        <h1 class="text-gray-800 font-bold text-2xl uppercase">To-Do List</h1>
    </div>
    <form class="w-full max-w-sm mx-auto px-4 py-2">
        <div class="flex items-center border-b-2 border-teal-500 py-2">
            <input
                class="appearance-none bg-transparent border-none w-full text-gray-700 mr-3 py-1 px-2 leading-tight focus:outline-none"
                type="text" placeholder="Add a task">
            <button
                class="flex-shrink-0 bg-teal-500 hover:bg-teal-700 border-teal-500 hover:border-teal-700 text-sm border-4 text-white py-1 px-2 rounded"
                type="button">
                Add
            </button>
        </div>
    </form>
    <ul class="divide-y divide-gray-200 px-4">
        <li class="py-4">
            <div class="flex items-center">
                <input id="todo1" name="todo1" type="checkbox"
                    class="h-4 w-4 text-teal-600 focus:ring-teal-500 border-gray-300 rounded">
                <label for="todo1" class="ml-3 block text-gray-900">
                    <span class="text-lg font-medium">Finish project proposal</span>
                    <span class="text-sm font-light text-gray-500">Due on 4/1/23</span>
                </label>
            </div>
        </li>
        <li class="py-4">
            <div class="flex items-center">
                <input id="todo2" name="todo2" type="checkbox"
                    class="h-4 w-4 text-teal-600 focus:ring-teal-500 border-gray-300 rounded">
                <label for="todo2" class="ml-3 block text-gray-900">
                    <span class="text-lg font-medium">Buy groceries</span>
                    <span class="text-sm font-light text-gray-500">Bananas, milk, bread</span>
                </label>
            </div>
        </li>
        <li class="py-4">
            <div class="flex items-center">
                <input id="todo3" name="todo3" type="checkbox"
                    class="h-4 w-4 text-teal-600 focus:ring-teal-500 border-gray-300 rounded">
                <label for="todo3" class="ml-3 block text-gray-900">
                    <span class="text-lg font-medium">Go for a run</span>
                    <span class="text-sm font-light text-gray-500">3 miles</span>
                </label>
            </div>
        </li>
    </ul>
</div>

</template>