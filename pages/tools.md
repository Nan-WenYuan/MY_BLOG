---
title: 效率工具
aside: false
---

<script setup>
import Banner from "@/components/Banner.vue";
import LinkList from "@/components/List/LinkList.vue";
import toolsData from "@/assets/toolsData.mjs";
</script>

<Banner
  type="page"
  title="效率工具"
  desc="开发生产力"
  footer="你有这么高速运转的机械进入中国，就看看下面的内容"
  image="https://cdn.jsdelivr.net/gh/Nan-WenYuan/picx-images-hosting@master/Banner/File_7.png"
/>

<!-- 工具数据 -->

<LinkList :listData="toolsData" :showCount="false" />
