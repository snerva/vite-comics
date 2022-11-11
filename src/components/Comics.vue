<script>
import comics from '../data/comics';
export default {
    name: 'Comics',
    data() {
        return {
            comics: comics
        }
    }
}
</script>

<template>
    <div class="col" v-for="comic in comics">
        <img :src="comic.thumb" alt="">
        <p>{{ comic.series }}</p>
    </div>
</template>