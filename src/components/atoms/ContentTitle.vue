<template>
  <p class="font-mono font-semibold whitespace-pre-wrap" :class="text_class">
    {{ title }}
  </p>
</template>

<script setup lang="ts">
type Props = {
  title: String;
  text_class?: String;
};

defineProps<Props>();
</script>
