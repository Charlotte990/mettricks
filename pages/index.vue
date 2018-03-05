<template>
<v-container grid-list-md text-xs-center>
    <v-layout row wrap>
      <v-flex xs12>
        <v-card dark color="white black--text">
          <v-card-text class="px-0">C H A R L O T T E</v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs12>
        <v-card light flat class="text-xs-center">
          <v-card-text class="px-0">
            <img src="/catgrey.jpeg" alt="Vuetify.js" />
            <img src="/catgrey.jpeg" alt="Vuetify.js" />
            <img src="/catgrey.jpeg" alt="Vuetify.js" />
            <img src="/catgrey.jpeg" alt="Vuetify.js" />
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
