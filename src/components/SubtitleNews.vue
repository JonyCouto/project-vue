<template>
    <v-row>
        <v-col cols="12">
            <h2 class="h2">{{ props.subtitle }}</h2>
        </v-col>
    </v-row>
</template>

<script setup lang="ts">
const props = defineProps({
    subtitle: String
});
</script>

<style lang="scss">
.h2 {
    color: grey;
    text-align: center;
}
</style>
