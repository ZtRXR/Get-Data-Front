<script lang="ts" setup>
import { NLayout,NLayoutHeader,NLayoutContent,NLayoutFooter } from "naive-ui"


</script>

<template>
    <n-layout>
      <n-layout-header style="min-height: 30px;">Header</n-layout-header>
      <n-layout-content content-style="padding: 24px;" style="min-height: 500px;">
        Text
      </n-layout-content>
      <n-layout-footer>footer</n-layout-footer>
    </n-layout>
</template>

<style scoped>
</style>