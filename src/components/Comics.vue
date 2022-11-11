<script>
import comics from '../data/comics';
import ComicItem from './ComicItem.vue';
export default {
    name: 'Comics',
    components: {
        ComicItem
    },
    data() {
        return {
            comics: comics
        }
    }
}
</script>

<template>
    <ComicItem v-for="comic in comics" :image="comic.thumb" :title="comic.series" />
</template>