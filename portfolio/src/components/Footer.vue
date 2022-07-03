<template>
  <v-footer dark padless>
    <v-card
      flat
      tile
      class="black white--text py-5 px-5 text-center"
      width="100%"
    >
      <v-row>
        <v-col cols="12" sm="4">
          <v-card-text class="white--text pt-2">
            <v-btn icon>
              <v-icon color="#A7121D">mdi-coffee</v-icon>
            </v-btn>
          </v-card-text>
        </v-col>
        <v-col cols="12" sm="4">
          <v-card-text class="pt-2">
            <v-btn class="mx-1 white--text" icon>
              <a
                class="white--text"
                href="https://www.linkedin.com/in/bruna-varela-1124021b3/"
                target="_blank"
              >
                <v-icon size="24px">mdi-linkedin</v-icon></a
              >
            </v-btn>
            <v-btn class="mx-1 white--text" icon>
              <a
                class="white--text"
                href="https://github.com/brunavarela"
                target="_blank"
              >
                <v-icon size="24px">mdi-github</v-icon>
              </a>
            </v-btn>
          </v-card-text>
        </v-col>
      </v-row>
    </v-card>
  </v-footer>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  text-decoration: none;
}
</style>
