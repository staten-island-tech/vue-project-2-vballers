<template>
    <div class="TopBorder">
        <h2 class="titleHome">Home</h2>
        <h2 class="titlePlayers">Players</h2>
        <button @click="$emit('add')" class="HomeButton">Home</button>
        <a href="secret">Home</a>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

.titleHome {
    color:green
}

</style>