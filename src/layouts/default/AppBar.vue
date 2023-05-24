<template>
  <v-app-bar flat class="text-center ">
    <v-app-bar-title>
      <v-icon icon="mdi-circle-slice-4" />
      Essentials Preset
    </v-app-bar-title>
    <template #append >
      <v-badge :content="5" class="pr-3">
        <v-icon icon="mdi-cart" size="x-large"></v-icon>
      </v-badge>
    </template>
  </v-app-bar>
</template>

<script setup>
  //
</script>
