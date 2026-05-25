<template>
  <header class="flex h-16 items-center justify-between border-b border-gray-300 px-5 shadow-sm bg-white">
    <!-- 왼쪽 로고 -->
    <h1 class="text-2xl font-bold text-black">
      Notes
    </h1>

    <!-- 가운데 검색창 -->
    <!-- <div class="relative w-[420px]">
      <input
        type="text"
        placeholder="Search Notes"
        class="w-full rounded-md bg-gray-100 px-5 py-3 pr-12 text-sm outline-none placeholder:text-gray-400"
      />

      <span class="absolute right-4 top-1/2 -translate-y-1/2 text-gray-400">
        🔍
      </span>
    </div> -->

    <!-- 오른쪽 유저 -->
    <div class="flex items-center gap-4">
      <div class="flex h-12 w-12 items-center justify-center rounded-full bg-gray-100 font-bold">
        TU
      </div>

      <div>
        <p class="font-bold text-black">유저</p>
        <button class="underline">
          로그아웃
        </button>
      </div>
    </div>
  </header>
</template>

<script setup>
</script>

<style scoped lang="scss">
</style>