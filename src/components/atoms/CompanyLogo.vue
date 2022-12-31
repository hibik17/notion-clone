<template>
  <img :src="`${logo}`" alt="company logo" class="object-cover w-20" />
</template>

<script setup lang="ts">
type Props = {
  logo?: String;
};

defineProps<Props>();
</script>
