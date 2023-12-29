<template>
  <div>
  <Nav></Nav>
    <slot />  
  </div>
</template>
<script setup lang="ts">
  import Nav from '~/components/nav.vue';
</script>
