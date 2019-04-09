<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-xs-center">
        <logo v-if="false" />
        <vuetify-logo v-if="false" />
      </div>
      <v-card>
        <v-card-text>
          <p>Ja, Miloš Spasojević, sam najbolji programer. I zato...</p>
        </v-card-text>
        <v-card-title class="headline">Pohvalite.me</v-card-title>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" flat nuxt to="/inspire">Continue</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
