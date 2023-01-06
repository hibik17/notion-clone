<template>
  <div class="w-[87%] mx-auto">
    <HeaderLayout />
    <FirstContent />
    <SecondContent />
    <div class="my-[50px]">
      <hr />
    </div>
    <div class="grid grid-cols-3">
      <div class="w-full h-full col-span-2 bg-red-300">white</div>
      <div class="w-full h-full bg-slate-300">ben white</div>
    </div>
  </div>
</template>

<script setup lang="ts">
import HeaderLayout from "@/components/templates/HeaderLayout.vue";
import FirstContent from "@/components/organisms/FirstContent.vue";
import SecondContent from "@/components/organisms/SecondContent.vue";
</script>
