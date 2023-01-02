<template>
  <div class="grid grid-cols-3 items-center justify-center text-[11px] pt-3">
    <!-- left part -->
    <div class="col-span-2">
      <div class="flex">
        <nav class="w-full">
          <ul class="flex">
            <li class="flex pr-[80px]">
              <img
                src="../../assets/notion.png"
                alt="notion icon"
                class="w-4 h-4"
              />
              <span class="px-1 font-serif">Notion</span>
            </li>
            <li class="pr-3">製品</li>
            <li class="pr-3">ダウンロード</li>
            <li class="pr-3">ソリューション</li>
            <li class="pr-3">リソース</li>
            <li>料金</li>
          </ul>
        </nav>
      </div>
    </div>
    <div class="col-span-1">
      <nav>
        <ul class="flex">
          <li class="pr-3">セールスへのお問い合わせ</li>
          <li class="pr-3">|</li>
          <li class="pr-3">ログイン</li>
          <li class="btn bg-red-500 px-2 py-[5px] text-white rounded-md">
            使ってみる
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script setup lang="ts"></script>
