<template>
  <div>
    <h2>{{ animal.name }}</h2>
    <h3>{{ animal.species }}</h3>
  </div>
</template>

<script setup>
defineProps({
  animal: {
    type: Object,
    required: true,
  },
})
</script>

<style scoped>
div {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
  height: 300px;
  width: 200px;
  border: 3px solid black;
}
</style>
