<template>
  <v-footer dark padless>
    <v-card flat tile class="black accent-4 lighten-1 white--text text-center" width="100%">
      <v-card-text>
        <v-btn v-for="icon in icons" :key="icon" class="mx-4 white--text" icon>
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-text>
      <v-card-text class="white--text pt-0">
       Andrea Leal
      </v-card-text>
      <v-divider></v-divider>
    </v-card>
  </v-footer>
</template>
<script>

export default {
  name: "Footer",
  data() {
    return {
      icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],
    }
  },
}

</script>

<style scoped>

</style>