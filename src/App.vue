<template>
  <LoaderBg/>
  <NavSidebar/>
  <HeaderBar/>

  <div class="pc-container">
    <div class="pc-container">
      <BreadCrumb/>
      
      <RouterView/>
    </div>
  </div>

  <FooterBar/>
</template>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
import NavSidebar from './components/layout/NavSidebar.vue';
import HeaderBar from './components/layout/HeaderBar.vue';
import FooterBar from './components/layout/FooterBar.vue';
import BreadCrumb from './components/layout/BreadCrumb.vue';
import LoaderBg from './components/layout/LoaderBg.vue';
</script>

<style scoped></style>
