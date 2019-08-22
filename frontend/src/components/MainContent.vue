<template>
    <div class="content">
        This is Main Content
    </div>
</template>

<script>
    export default {
        name: "MainContent"
    }
</script>

<style scoped>
    .content {
        grid-column: 2/3;
        border: 1px solid red;
        display: grid;
        justify-content: center;
        align-items: center;
    }
</style>