<template>
  <div class="app">This is App</div>
</template>

<script>
import { defineComponent } from 'vue'

import Button from './Button.tsx'

export default defineComponent({
  setup() {
    console.log('---', ACCESS, UNDEF)
  }
})
</script>
