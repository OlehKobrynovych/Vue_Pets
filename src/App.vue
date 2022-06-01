<template>
  <div class="container-wrap" id="app">
    <Navbar />
    <Info/>
    <SearchHome/>
    <Find/>
    <router-view/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Info from './components/Info.vue';
import SearchHome from './components/SearchHome.vue';
import Find from './components/Find.vue';
export default {
    name: "App",
    components: { Navbar, Info, SearchHome, Find }
}
</script>

<style>

</style>
