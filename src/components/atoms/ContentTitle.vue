<template>
  <p class="font-mono font-semibold whitespace-pre-wrap">
    {{ title }}
  </p>
</template>

<script setup lang="ts">
type Props = {
  title: String;
};

defineProps<Props>();
</script>
