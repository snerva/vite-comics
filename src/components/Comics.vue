<script>
import comics from '../data/comics';
import Comic from './Comic.vue';
export default {
    name: 'Comics',
    components: {
        Comic
    },
    data() {
        return {
            comics: comics
        }
    }
}
</script>

<template>
    <Comic v-for="comic in comics" :image="comic.thumb" :title="comic.series" />
</template>