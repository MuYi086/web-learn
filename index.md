---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "web-secret"
  text: ""
  tagline: 学习、记录、总结 Web 相关技术
---
<script setup>
import { ref } from 'vue'
const rowWrapVal = ref(true)
</script>

<!-- Images -->
<a-divider orientation="left">Images</a-divider>
<a-row justify="start">
  <a-button href="/Docs/Images/图片和效果">图片和效果</a-button>
  <a-button href="/Docs/Images/性能问题">性能问题</a-button>
  <a-button href="/Docs/Images/图片格式和压缩">图片格式和压缩</a-button>
  <a-button href="/Docs/Images/自适应图片">自适应图片</a-button>
  <a-button href="/Docs/Images/高性能映像工作流">高性能映像工作流</a-button>
</a-row>
