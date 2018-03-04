<template>
<v-container grid-list-md text-xs-center>
    <v-layout column row wrap justify-center align-center>
      <v-flex xs12 sm8 md6>
        <v-card light>
          <v-card-text class="px-0">
            <img src="Charlotteheart.svg" alt="Vuetify.js" />
          </v-card-text>
        </v-card>
      </v-flex>
      <v-flex>
        <v-card light color="pink">
          <v-card-title class="headline">NO.</v-card-title>
            <v-card-text>
              <v-btn color="warning">FUCK OFF.</v-btn>          
            </v-card-text>
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn flat nuxt to="/inspire">Continue</v-btn>
            </v-card-actions>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template
