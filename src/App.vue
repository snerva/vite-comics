<script>
import SiteHeader from './components/SiteHeader.vue';
import SiteMain from './components/SiteMain.vue';
export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain,
  }
}
</script>

<template>
  <SiteHeader></SiteHeader>
  <SiteMain></SiteMain>

  <footer id="site_footer">
    <div class="footer_top">
      <div class="container">
        <div class="footer_menu">
          <div class="row">
            <div class="col"></div>
            <div class="col"></div>
            <div class="col"></div>
          </div>
        </div>
        <div class="background_logo"></div>
      </div>
    </div>

    <div class="footer_bottom">
      <div class="container">
        <div class="sign_up"></div>
        <div class="follow_us"></div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">

</style>
