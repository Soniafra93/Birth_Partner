<template>
  <div class="min-h-screen flex flex-col pt-16 pb-16">
    <Header class="fixed top-0 inset-x-0 w-full z-50" />
    <MainBody class="flex-1" />
    <NuxtRouteAnnouncer />
    <Footer class="fixed bottom-0 inset-x-0 w-full z-50" />
  </div>
</template>
<script lang="ts">
import Header from "./components/Header.vue";
</script>
