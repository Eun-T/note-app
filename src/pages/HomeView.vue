<template>
  <div class="w-full h-full py-10 px-[60px] grid grid-cols-3 gap-y-5">
    <NoteCard v-for="card in cards" :key="card.title" :card="card" />
  </div>
</template>

<script setup>
import NoteCard from '@/components/note/NoteCard.vue'

let cards = [
  {
    title: 'Practice Mindfulness Meditation',
    birth: '6th Apr 2024',
    content: 'Lorem ipsum dolor sit amet?',
    tags: 'Meditation',
  },
  {
    title: 'Plan Weekend Getaway',
    birth: '6th Apr 2024',
    content: 'Lorem ipsum dolor sit amet?',
    tags: 'Meditation',
  },
]
</script>

<style scoped lang="scss"></style>
