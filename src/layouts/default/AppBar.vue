<template>
  <v-app-bar flat class="text-center ">
    <v-app-bar-title>
      <v-icon icon="mdi-circle-slice-4" />
      Essentials Preset
    </v-app-bar-title>
    <template #append >
      <v-badge :content="5" class="pr-3">
        <v-icon icon="mdi-cart" size="x-large" @click.stop="drawer = !drawer"></v-icon>
      </v-badge>
    </template>
  </v-app-bar>
  <v-navigation-drawer v-model="drawer" temporary location="right" >
    <v-card>

    </v-card>
  </v-navigation-drawer>
  
</template>

<script>
  export default {
    data () {
      return {
        drawer: null,
      }
    },
  }
</script>
