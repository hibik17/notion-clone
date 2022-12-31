<template>
  <div class="mt-[70px]">
    <div class="grid grid-cols-2 gap-2">
      <div class="h-56">
        <FirstContentTitle />
        <ContentText :content="mainContent" />
        <RedButton />
        <ContentText :content="subContent" />
        <!-- 協賛企業紹介 -->
        <div class="grid grid-cols-5 gap-1">
          <div>
            <img
              src="https://images.ctfassets.net/spoqsaf9291f/37B7qVI9fp06fAJU1ixRim/41a0d5f4c8d867e86c08c5defc6c26f3/mitsubishi-logo.png"
              alt="company logo"
            />
          </div>
          <div>
            <img
              src="https://images.ctfassets.net/spoqsaf9291f/37B7qVI9fp06fAJU1ixRim/41a0d5f4c8d867e86c08c5defc6c26f3/mitsubishi-logo.png"
              alt="company logo"
            />
          </div>
          <div>
            <img
              src="https://images.ctfassets.net/spoqsaf9291f/37B7qVI9fp06fAJU1ixRim/41a0d5f4c8d867e86c08c5defc6c26f3/mitsubishi-logo.png"
              alt="company logo"
            />
          </div>
          <div>
            <img
              src="https://images.ctfassets.net/spoqsaf9291f/37B7qVI9fp06fAJU1ixRim/41a0d5f4c8d867e86c08c5defc6c26f3/mitsubishi-logo.png"
              alt="company logo"
            />
          </div>
          <div>
            <img
              src="https://images.ctfassets.net/spoqsaf9291f/37B7qVI9fp06fAJU1ixRim/41a0d5f4c8d867e86c08c5defc6c26f3/mitsubishi-logo.png"
              alt="company logo"
            />
          </div>
        </div>
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

const mainContent = `Notionは単なるドキュメントやテーブルではありま
せん。望み通りに機能するようにNotionをカスタマ
イズしましょう。`;

const subContent = "多くの企業から信頼を得ています";
</script>
