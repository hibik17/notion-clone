<template>
  <div class="grid w-full grid-cols-3 gap-[50px] mt-[80px]">
    <div class="col-span-2">
      <img :src="`${image_path}`" alt="notion image" />
    </div>
    <div class="col-span-1">
      <div class="flex items-center justify-center w-full h-full">
        <div>
          <!-- LOGO -->
          <img
            :src="`${icon_path}`"
            alt="second icon"
            class="w-1/3 drop-shadow-2lg"
          />
          <!-- Title -->
          <p class="font-mono font-semibold whitespace-pre-wrap">
            {{ title }}
          </p>
          <!-- Body -->
          <ContentText :content="content" />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import ContentText from "../atoms/ContentText.vue";

type Props = {
  title: String;
  content: String;
  image_path: String;
  icon_path: String;
};

defineProps<Props>();
</script>
