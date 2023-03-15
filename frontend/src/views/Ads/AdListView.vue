<template>
  <v-container>
      <h1 class="text--secondary mb-3 mt-3">My ads</h1>
      <v-card class="mx-auto" max-width="1000">
          <v-row>
              <v-img height="175px"></v-img>
              <v-spacer></v-spacer>
          </v-row>
          <v-row>
              <v-card-text>
                  <h2 class="text--primary">{{  }}</h2>
                  <p>{{  }}</p>
              </v-card-text>
              <v-card-actions>
                  <v-spacer></v-spacer>
                  <v-btn color="primary" variant="text" >Open</v-btn>
                  <v-spacer></v-spacer>
              </v-card-actions>
          </v-row>
      </v-card>
  </v-container>
</template>


<script>
export default {
  data() {
      return {
         
      }
  }
};
</script>