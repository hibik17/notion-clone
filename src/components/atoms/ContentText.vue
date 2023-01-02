<template>
  <p class="text-sm whitespace-pre-line text-slate-400">{{ content }}</p>
</template>

<script setup lang="ts">
type Props = {
  content: String;
};

const { content } = defineProps<Props>();

// 受け取ったpropsの中に改行が含まれている場合に改行して表示するためのメソッド
if (content.search("<br>")) {
  content.split("<br>").map((line) => {
    console.log(line);
  });
}
</script>
