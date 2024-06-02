<template>
    <v-row>
        <v-col cols="12">
            <h1 class="title">{{ props.title }}</h1>
        </v-col>
    </v-row>
</template>

<script setup lang="ts">
const props = defineProps({
    title: String
});
</script>

<style lang="scss" scoped>
.title {
    color: rgb(170, 5, 5);
    text-align: center;
}
</style>
