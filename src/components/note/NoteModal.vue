<template>
  <div class="fixed inset-0 bg-black/50 flex items-center justify-center">
    <div class="w-[600px] h-[500px] bg-white p-5 flex flex-col gap-1 rounded-[8px]">
      <div>
        <div class="flex justify-between items-center">
          <h3 class="text-sm">제목</h3>
          <X class="w-5 h-5 text-gray-500"/>
        </div>
        <input type="text" class="h-10 outline-none text-2xl" placeholder="제목" />
      </div>
      <div class="flex flex-col gap-2 mb-3">
        <h3 class="text-sm">내용</h3>
        <textarea
          name=""
          id=""
          class="w-full h-[230px] outline-none bg-gray-100 p-3"
          placeholder="내용"
        ></textarea>
      </div>
      <div class="mb-3">
        <h3>태그</h3>
        <div class="flex items-center gap-3">
          <input
            type="text"
            class="h-[30px] w-[140px] px-1 border outline-none border-gray-300"
            placeholder="태그 추가"
          />
          <Plus class="w-7 h-7 border rounded-[4px] text-blue-500" />
        </div>
      </div>
      <button class="bg-blue-500 w-full h-10 rounded-[6px] text-sm text-white">추가</button>
    </div>
  </div>
</template>

<script setup>
import { Plus, X } from 'lucide-vue-next'
</script>

<style scoped lang="scss"></style>
