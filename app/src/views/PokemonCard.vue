<template>
    <div>
<h2>{{ pokemon.name }}</h2>
<h3> {{ id }}</h3>
    </div>
</template>

<script setup>
const props = defineProps({
    pokemon: {
        type: Number,
        required: true, 
    }
})
</script>

<style lang="scss" scoped>

</style>