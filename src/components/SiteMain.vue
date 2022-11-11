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
                <div class="label">
                    <h2>current series</h2>
                </div>
                <div class="comics">
                    <div class="row row-cols-6 g-4">
                        <div class="col">
                            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                                alt="">
                            <p>action comics</p>
                        </div>
                        <div class="col">
                            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                                alt="">
                            <p>action comics</p>
                        </div>
                        <div class="col">
                            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                                alt="">
                            <p>action comics</p>
                        </div>
                        <div class="col">
                            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                                alt="">
                            <p>action comics</p>
                        </div>
                        <div class="col">
                            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                                alt="">
                            <p>action comics</p>
                        </div>
                        <div class="col">
                            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                                alt="">
                            <p>action comics</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <SiteMainBluePanel></SiteMainBluePanel>

    </main>
</template>

<style lang="scss" scoped>

</style>