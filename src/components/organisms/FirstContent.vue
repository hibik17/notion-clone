<template>
  <div class="mt-[70px]">
    <div class="grid grid-cols-2 gap-2">
      <div class="h-56">
        <FirstContentTitle />
        <ContentText :content="mainContent" />
        <Button :color="'bg-red-400'" />
        <ContentText :content="subContent" />
        <!-- 協賛企業紹介 -->
        <div class="grid grid-cols-5 gap-1">
          <CompanyLogos />
        </div>
      </div>
      <div class="flex justify-end w-full h-56">
        <FirstContentImgVue />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import FirstContentImgVue from "../atoms/FirstContentImg.vue";
import FirstContentTitle from "../atoms/FirstContentTitle.vue";
import ContentText from "../atoms/ContentText.vue";
import Button from "../atoms/Button.vue";
import CompanyLogos from "../molecules/CompanyLogos.vue";

const mainContent = `Notionは単なるドキュメントやテーブルではありま
せん。望み通りに機能するようにNotionをカスタマ
イズしましょう。`;

const subContent = "多くの企業から信頼を得ています";
</script>
