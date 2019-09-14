<template>
  <v-app id="inspire">
    
    <v-app-bar
      app
      clipped-left
    >
      <v-toolbar-title>Henry Hayden</v-toolbar-title>
    </v-app-bar>

    <v-card
    
    class="mx-auto"
  >
    <v-card-title>My name is Henry Hayden, and I'm a software engineer with a preference for front-end design.</v-card-title>
    <v-card-text>I'm card text</v-card-text>
    <v-card-actions>
      <v-btn text>Click</v-btn>
    </v-card-actions>
  </v-card>

    <!-- <v-content>
      <v-container
        class="fill-height"
        fluid
      >
        <v-row
          align="center"
          justify="center"
        >
          <v-col class="shrink">
          </v-col>
        </v-row>
      </v-container>
    </v-content> -->
  </v-app>
</template>

<script>
  export default {
    props: {
      source: String,
    },
    data: () => ({
      drawer: null,
    }),
    created () {
      this.$vuetify.theme.dark = true
    },
  }
</script>