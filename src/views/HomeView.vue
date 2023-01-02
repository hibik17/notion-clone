<template>
  <div class="w-[87%] mx-auto">
    <HeaderLayout />
    <FirstContent />
    <SecondContent />
    <div class="my-[50px]">
      <hr />
    </div>
  </div>
</template>

<script setup lang="ts">
import HeaderLayout from "@/components/templates/HeaderLayout.vue";
import FirstContent from "@/components/organisms/FirstContent.vue";
import SecondContent from "@/components/organisms/SecondContent.vue";
</script>
