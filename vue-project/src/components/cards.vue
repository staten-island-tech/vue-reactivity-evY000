<template>
    <div class="Card"> <h1 class="text">{{ Name }}<img class="img" :src="Image"> <button class="btn" type="button">Select</button>  </h1></div>
</template>
<script setup>
const props = defineProps({
   Name: String,
    Image : String,
})
</script>
<style lang="scss" scoped>
</style>