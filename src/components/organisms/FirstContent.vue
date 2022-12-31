<template>
  <div class="mt-[70px]">
    <div class="grid grid-cols-2 gap-2">
      <div class="h-56">
        <FirstContentTitle />
        <ContentText />
        <ContentText />
        <RedButton />
      </div>
      <div class="w-full h-56 flex justify-end">
        <FirstContentImgVue />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import FirstContentImgVue from "../atoms/FirstContentImg.vue";
import FirstContentTitle from "../atoms/FirstContentTitle.vue";
import ContentText from "../atoms/ContentText.vue";
import RedButton from "../atoms/RedButton.vue";
</script>
