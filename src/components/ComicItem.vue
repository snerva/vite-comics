<script>
export default {
    props: {
        image: String,
        title: String
    }
}
</script>

<template>
    <div class="col">
        <img :src="image" alt="">
        <p>{{ title }}</p>
    </div>
</template>