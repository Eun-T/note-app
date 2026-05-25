<template>
  <div
    class="w-[450px] bg-white h-[135px] p-3 flex flex-col gap-0.5 border border-gray-200 rounded-md bg-white shadow-sm"
  >
    <div class="flex justify-between items-center">
      <div>
        <h3 class="font-bold">{{ card.title }}</h3>
        <p>{{ card.birth }}</p>
      </div>
      <Pin class="h-5 w-5 text-gray-500" />
    </div>
    <p class="truncate">{{ card.content }}</p>
    <div class="flex justify-between">
      <span>{{ card.tags }}</span>
      <div class="flex gap-2.5 text-gray-500">
        <Pen class="h-5 w-5" />
        <Trash class="h-5 w-5" />
      </div>
    </div>
  </div>
</template>

<script setup>
import { Pen, Trash, Pin } from 'lucide-vue-next'
defineProps({
  card: Object,
})
</script>

<style scoped lang="scss"></style>
