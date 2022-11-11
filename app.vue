<script setup lang="ts">
// import Helloworld from './src/pages/Helloworld.vue'
import Test from '@c/Test.vue'
// import Test from '@@/src/components/Test.vue'
const runtimeConfigKey = useRuntimeConfig()
const appConfigValue = useAppConfig()
// const { curTime } = useGetTime()
</script>

<template>
  <div>
    <!-- <NuxtWelcome /> -->
    {{ runtimeConfigKey }}
    {{ appConfigValue }}
    <Test />
  </div>
</template>
