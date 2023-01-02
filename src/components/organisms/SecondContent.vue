<template>
  <div v-for="(content, index) in contents" :key="index">
    <DemoContent
      :title="content.title"
      :content="content.content"
      :image_path="content.image_path"
      :icon_path="content.icon_path"
    />
  </div>
</template>

<script setup lang="ts">
import DemoContent from "../molecules/DemoContent.vue";
// 画像とアイコンをimport
import SecondImg from "../../assets/SecondImg.png";
import SecondIcon from "../../assets/SecondIcon.png";
import ThirdImg from "../../assets/ThirdImg.png";
import ThirdIcon from "../../assets/ThirdIcon.png";
import FourthImg from "../../assets/FourthImg.png";
import FourthIcon from "../../assets/FourthIcon.png";
import FifthImg from "../../assets/FifthImg.png";
import FifthIcon from "../../assets/FifthIcon.png";

type contentType = {
  title: String;
  content: String;
  image_path: String;
  icon_path: String;
};

const contents: Array<contentType> = [
  {
    title: "混乱することなくチームを立ち 上げ",
    content:
      "チーム、プロジェクト、ドキュメントをNotionでつなぐことで、情報の分断を解消して一丸となって作業できます。",
    image_path: SecondImg,
    icon_path: SecondIcon,
  },
  {
    title: "「どういう状況ですか？」と 尋ねる必要がなくなります。",
    content:
      "古くなったWikiや、整理されていないドキュメントは 役に立ちません。Notionでは、日常業務と知識が一元 管理されるので、常に状況を把握できます。",
    image_path: ThirdImg,
    icon_path: ThirdIcon,
  },
  {
    title: "思い通りのワークフローを構 築する",
    content:
      "望み通りに機能するようにNotionをカスタマイズしま す。 ドラッグ＆ドロップするだけで、必要なダッシュ ボード、Webサイト、ドキュメント、システムなどを 作成できます。",
    image_path: FourthImg,
    icon_path: FourthIcon,
  },
  {
    title: "クリエイターたちのグローバ ルなエコシステムを活用する",
    content:
      "コミュニティで作成された何千ものテンプレート、イ ンテグレーション、イベントからインスピレーション を得ましょう。 リソースやサポートが不足することはありません。",
    image_path: FifthImg,
    icon_path: FifthIcon,
  },
];
</script>
