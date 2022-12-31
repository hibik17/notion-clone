<template>
  <img :src="`${logo}`" alt="company logo" class="object-fill h-5 w-15" />
</template>

<script setup lang="ts">
type Props = {
  logo?: String;
};

defineProps<Props>();
</script>
