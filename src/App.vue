<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

  export default {
    components: { AppTitle, AppHero },
    data() {
        return {};
    },
    methods: {},
}
</script>

<template>
  <div class="container">
    <AppTitle></AppTitle>
    <AppHero></AppHero>
  </div>
</template>

<style scoped>
</style>
