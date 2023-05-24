<template>
  <v-footer class="flex-column w-100" >
    <div class="px-4 py-2 bg-black text-center w-100">
      <strong> Weverton</strong> — {{ new Date().getFullYear() }}  
    </div>
    <div class="bg-teal d-flex w-100 align-center px-4">
      <strong>Get connected with us on social networks!</strong>
      <v-spacer></v-spacer>
      <v-btn v-for="icon in icons" :key="icon"
        class="mx-1"
        :icon="icon.logo"
        :to="icon.link"
        variant="plain" size="small"
      ></v-btn>
    </div>
  </v-footer>
</template>

<script>
  export default {
    data: () => ({
      icons: [
        {logo:'mdi-facebook', link:'facebook'},
        {logo:'mdi-twitter', link:'twitter'},
        {logo:'mdi-linkedin', link:'linkedin'},
        {logo:'mdi-instagram', link:'instagram'},
      ],
    }),
  }
</script>
