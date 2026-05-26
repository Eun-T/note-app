<template>
  <div @click ="openModal">
    <button
      class="fixed bottom-8 right-8 flex h-16 w-16 items-center justify-center rounded-2xl bg-blue-600 text-white shadow-lg hover:bg-blue-700 hover:scale-105 transition"
    >
      <Plus />
    </button>
  </div>
</template>

<script setup>
import { Plus } from 'lucide-vue-next'

const emit = defineEmits(['open'])

const openModal = () => {
  emit('open')
}

</script>

<style scoped lang="scss"></style>
