<template>
  <div id="app" class="container">
      <SiteHeader />
      <router-view />
      <SiteFooter />
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue';
import SiteFooter from './components/SiteFooter.vue';

export default {
    components: {
        SiteHeader,
        SiteFooter,
    },
};
</script>
