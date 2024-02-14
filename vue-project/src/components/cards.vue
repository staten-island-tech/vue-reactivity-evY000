
<template>
    <div> <h1 class="text">{{ Name }}<img class="img" :src="Image"> </h1></div>
</template>
<script setup>
const props = defineProps({
   Name: String,
    Image : String
})
</script>
<style lang="scss" scoped>
</style>