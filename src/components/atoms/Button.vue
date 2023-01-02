<template>
  <div
    class="btn w-[180px] text-center text-sm bg-red-500 text-white rounded-sm shadow-sm my-2"
  >
    Notionを無料で使ってみる
  </div>
</template>

<script setup lang="ts">
type Props = {
  color: string;
};

defineProps<Props>();
</script>
