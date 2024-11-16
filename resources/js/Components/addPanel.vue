<template>
    <div class="mx-10">
        <div class="flex border-b border-gray-300">
            <button
                class="w-1/2 py-4 text-center font-medium text-gray-700 bg-gray-100 rounded-tl-lg focus:outline-none active:bg-gray-200"
                @click="openTab(event, 'tab1')"
            >
                Details
            </button>
            <button
                class="w-1/2 py-4 text-center font-medium text-gray-700 bg-gray-100 rounded-tr-lg focus:outline-none"
                @click="openTab(event, 'tab2')"
            >
                Parents and children
            </button>

            <button
                class="w-1/2 py-4 text-center font-medium text-gray-700 bg-gray-100 rounded-tr-lg focus:outline-none"
                @click="openTab(event, 'tab3')"
            >
                life sphere weights
            </button>
            
        </div>
        <div id="tab1" class="tabcontent p-4">
            <h2 class="text-lg font-bold text-gray-800">Details</h2>
            <p class="mt-2 text-gray-700">
       plase for details component
            </p>
        </div>
        <div id="tab2" class="tabcontent p-4 hidden">
            <h2 class="text-lg font-bold text-gray-800">Parents and children</h2>
            <p class="mt-2 text-gray-700">
           plase for parents end details components
            </p>
        </div>
        <div id="tab3" class="tabcontent p-4 hidden">
            <h2 class="text-lg font-bold text-gray-800">Weight</h2>
            <p class="mt-2 text-gray-700">
           plase for life weight
            </p>
        </div>
    </div>
</template>

<script setup>

function openTab(evt, tabName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].classList.add("hidden");
    }
    tablinks = document.getElementsByTagName("button");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].classList.remove("active:bg-gray-200");
    }
    document.getElementById(tabName).classList.remove("hidden");
    evt.currentTarget.classList.add("active:bg-gray-200");
}
</script>
