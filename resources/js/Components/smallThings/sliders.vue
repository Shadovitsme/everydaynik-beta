<script setup>
import { ref, watch } from "vue";
// TODO сделать их количество меняющимся
const range1 = ref(50);
const range2 = ref(50);
const range3 = ref(50);
const range4 = ref(50);
const range = ref(0);

const on = ref(false);


const nums = [123, 543, 4634, 6473, 245];

watch(range1, (n, o) => {
  if (range.value == 1) {
    range3.value += (n - o) / 4;
    range2.value += (n - o) / 4;
    range4.value += (n - o) / 4;
  }
});
watch(range2, (n, o) => {
  if (range.value == 2) {
    range3.value += (n - o) / 4;
    range1.value += (n - o) / 4;
    range4.value += (n - o) / 4;
  }
});
watch(range3, (n, o) => {
  if (range.value == 3) {
    range1.value += (n - o) / 4;
    range2.value += (n - o) / 4;
    range4.value += (n - o) / 4;
  }
});
watch(range4, (n, o) => {
  if (range.value == 4) {
    range3.value += (n - o) / 4;
    range2.value += (n - o) / 4;
    range1.value += (n - o) / 4;
  }
});
</script>

<template>
<!-- TODO перекрасить в основной голубой -->
 <!-- TODO понять чего при увеличении одного увеличивается все -->
<div class="block">
  <div class="text-gray text-xs">sphere name</div>
  <input class="w-2/5 mb-3"
    v-model.number="range1"
    v-on="{
      mouseenter: () => (range = 1),
      focus: () => (range = 1),
    }"
    type="range"
  />
</div> 

<div class="block">
  <div class="text-gray text-xs">sphere name</div>
  <input class="w-2/5 mb-3"
    v-model.number="range2"
    v-on="{
      mouseenter: () => (range = 2),
      focus: () => (range = 2),
    }"
    type="range"
  />
</div> 

<div class="block">
  <div class="text-gray text-xs">sphere name</div>
  <input class="w-2/5 mb-3"
    v-model.number="range3"
    v-on="{
      mouseenter: () => (range = 3),
      focus: () => (range = 3),
    }"
    type="range"
  />
</div> 

<div class="block">
  <div class="text-gray text-xs">sphere name</div>
  <input class="w-2/5 mb-3"
    v-model.number="range4"
    @mouseenter="range = 4"
    @focus="range = 4"
    type="range"
  />
</div> 

</template>

<!-- <style scoped>
input,
p {
  width: 400px;
  display: block;
  margin: 3rem;
}
</style> -->
