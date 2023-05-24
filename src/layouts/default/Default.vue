<template>
  <v-app theme="dark">
    <v-container>
      <default-bar />
      <default-view />
      <default-footer />
    </v-container>
  </v-app>
</template>

<script setup>
  import DefaultBar from './AppBar.vue'
  import DefaultView from './View.vue'
  import DefaultFooter from './Footer.vue'
</script>
