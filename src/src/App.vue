<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <iframe
    ref="myIframe"
    src="https://dify.xsayai.com/chat/SqPwUWEKvMFSacNe"
    frameborder="0"
    scrolling="no"
  ></iframe>
  <!-- <RouterView /> -->
</template>

<style scoped>
iframe {
  width: 100%;
  height: 100%;
}
</style>
