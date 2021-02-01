<template>
  <v-bottom-navigation

    color="orange darken-4"
    grow
  >
    <v-btn>
      <span>Inicio</span>

      <v-icon>mdi-home</v-icon>
    </v-btn>

    <v-btn>
      <span>Favorites</span>

      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn>
      <span>Nearby</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
  </v-bottom-navigation>
</template>
<script>
export default {
  name: "Footer"
}
</script>
<style>
</style>
