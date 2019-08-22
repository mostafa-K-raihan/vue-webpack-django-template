<template>
    <div class="topbar">
        This is a topbar
    </div>
</template>

<script>
    export default {
        name: "Topbar"
    }
</script>

<style scoped>
    .topbar {
        grid-column: 1 / 3;
        grid-rows: 1 / 2;
        border: 1px solid red;
         display: grid;
        justify-content: center;
        align-items: center;

    }
</style>