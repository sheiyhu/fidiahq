<template>
  <div class="container">
    <sidebarComponent/>
    <div class="main">
      <navComponent/>
    <mainComponent/>
    </div>
  <div class="checkbox">
      <input id="null" type="checkbox" name="null">
    </div>
  </div>
</template>

<script>
import main from '~/components/main.vue';
import nav from '~/components/nav.vue';
import sidebar from '~/components/sidebar.vue';
  export default {
    components: {
      mainComponent: main,
      navComponent: nav,
      sidebarComponent: sidebar,
    },
  }
</script>

<style>
 @import '~/assets/dashboard.css';
</style>
