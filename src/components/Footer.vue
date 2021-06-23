<template>
  <v-footer dark padless>
    <v-card class="flex" flat tile>
      <v-card-title class="amber darken-4">
        <strong class="subheading">Tu servicio de carwash delivery</strong>
        <v-spacer></v-spacer>
      </v-card-title>
      <v-card-text class="py-2 white--text text-center">
        {{ new Date().getFullYear() }} — <strong>Carwash-Home</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>
<script>
export default {
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"]
  })
};
</script>
