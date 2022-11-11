<script>
import SiteMainBluePanel from './SiteMainBluePanel.vue';
import Comics from './Comics.vue';
export default {
    name: 'SiteMain',
    components: {
        SiteMainBluePanel,
        Comics
    }

}
</script>

<template>
    <main id="site_main">

        <div class="main_contents">
            <div class="main_banner"></div>
            <div class="container">
                <div class="label">
                    <h2>current series</h2>
                </div>
                <div class="comics">
                    <div class="row row-cols-6 g-4">
                        <Comics></Comics>
                    </div>
                </div>
            </div>
        </div>
        <SiteMainBluePanel></SiteMainBluePanel>

    </main>
</template>

<style lang="scss" scoped>

</style>