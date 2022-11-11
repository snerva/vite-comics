<script>
import SiteMainBluePanel from './SiteMainBluePanel.vue';
export default {
    name: 'SiteMain',
    components: {
        SiteMainBluePanel
    }

}
</script>

<template>
    <main id="site_main">

        <div class="main_contents">
            <div class="main_banner"></div>
            <div class="container">
                <div class="comics"></div>
            </div>
        </div>
        <SiteMainBluePanel></SiteMainBluePanel>

    </main>
</template>

<style lang="scss" scoped>

</style>