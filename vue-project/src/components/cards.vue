<template>
    <div class="Card"> <h1 class="text">{{ players.Name }}<img class="img" :src="players.Image"> <button class="btn" type="button">Select</button>  </h1></div>
</template>
<script setup>
const props = defineProps({
    players: Object
})
</script>
<style lang="scss" scoped>
</style>
<!-- V-for the cards
button
user input
turn mechanic
position mechanic -->