<script setup lang="ts">
// nuxt3 自动加入了 https://github.com/antfu/unplugin-auto-import 中的自动引入插件
// import { ref } from 'vue'
// import { useMouse } from '@vueuse/core'
const { x, y } = useMouse()
const msg = ref('a')
</script>

<template>
  <div class="maintain">
    {{ msg }}
    {{ x }}
    {{ y }}
  </div>
</template>
