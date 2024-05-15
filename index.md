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
</a-row>
