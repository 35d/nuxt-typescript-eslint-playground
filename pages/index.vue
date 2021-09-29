<template>
  <Tutorial />
</template>

<script lang="ts">
import { defineComponent } from '@nuxtjs/composition-api'

export default defineComponent({
  setup() {
    const a = 1 // 使用していない変数
    return {
      a,
    }
  },
})
</script>
