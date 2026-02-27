<template>
  <div>
    <itemcard vfor />
    <shoppingCart v-if="cart.length > 0" />
  </div>
</template>

<script setup>
import { reactive } from 'vue'

const cart = reactive
</script>

<style lang="scss" scoped></style>
