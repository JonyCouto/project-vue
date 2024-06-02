<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
    <main class="main">
        <RouterView />
    </main>
</template>

<style>
.main {
    background-color: rgb(50, 50, 50);
    min-height: 100%;
}
html,
body,
#app {
    height: 100%;
}
* {
    box-sizing: border-box;
}
</style>
