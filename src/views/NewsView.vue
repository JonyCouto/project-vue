<template>
    <v-container-fluid class="container">
        <div class="news">
            <TitleNews :title="props.title" />
            <SubtitleNews :subtitle="props.subtitle" />
            <DescriptionNews :description="props.description" />
            <RedirectNews />
        </div>
    </v-container-fluid>
</template>

<script setup lang="ts">
import TitleNews from '@/components/TitleNews.vue';
import SubtitleNews from '@/components/SubtitleNews.vue';
import RedirectNews from '@/components/RedirectNews.vue';
import DescriptionNews from '@/components/DescriptionNews.vue';
const props = defineProps({
    title: String,
    subtitle: String,
    description: String
});
</script>

<style lang="scss" scoped>
.news {
    background-color: #e7dfd1;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 2px 3px 4px rgb(25, 25, 25);
    margin: 10px 0px;
    h1 {
        color: blue;
    }
    h2 {
        color: grey;
    }
    a {
        color: blue;
        &:visited {
            color: blue;
        }
    }
}
</style>
