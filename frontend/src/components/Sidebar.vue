<template>
    <div class="sidebar">
        This is a sidebar
    </div>
</template>

<script>
    export default {
        name: "Sidebar"
    }
</script>

<style scoped>
    .sidebar {
        grid-column: 1 / 2;
        border: 1px solid red;
        display: grid;
        justify-content: center;
        align-items: center;
    }
</style>