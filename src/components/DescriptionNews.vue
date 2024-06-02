<template>
    <v-row>
        <v-col cols="12">
            <p class="p">{{ props.description }}</p>
        </v-col>
    </v-row>
</template>

<script setup lang="ts">
const props = defineProps({
    description: String
});
</script>

<style lang="scss">
.p {
    text-align: justify;
}
</style>
