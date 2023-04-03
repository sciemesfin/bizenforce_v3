<template>
    <div>
        <PublicToolbar/>

    <slot />
  
    <Footer/>
    </div>
  </template>

<script lang="ts" setup>
import PublicToolbar from '~~/components/layout/PublicToolbar.vue';
import Footer from '~~/components/layout/Footer.vue';
</script>