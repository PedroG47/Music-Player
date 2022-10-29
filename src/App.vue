<template>
  <v-app>
    <v-main class="d-flex justify-center align-center">
      <v-card
        class="mx-auto"
        max-width="400"
        height="450"
      >
        <v-img
          class="mx-auto"
          max-width="180"
          height="150"
          src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
        >
        </v-img>
        <v-card-title
          class="justify-center"
        >
          Nome da musica
        </v-card-title>
        <v-card-subtitle 
        class="text-center pb-0"
        >
          Nome do cantor/banda
        </v-card-subtitle>
        <v-card-subtitle 
        class="text-center pt-0"
        >
          Álbum
        </v-card-subtitle>

       <v-app-bar flat>
          <span class="caption text-9x1 ml-14">01:44</span>
          <v-slider value="25" color="orange" class="mt-6"></v-slider>
          <span class="caption text-9x1 mr-14">04:30</span>
       </v-app-bar>

        <div class="text-center">
          <v-btn icon class="mt-4">
              <v-icon>mdi-rewind</v-icon>
          </v-btn>

          <v-btn icon class="ml-14 mt-4">
              <v-icon>mdi-pause</v-icon>
          </v-btn>
          <v-btn icon class="ml-14 mt-4">
              <v-icon>mdi-fast-forward</v-icon>
          </v-btn>
        </div>
      </v-card>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  }),
};
</script>
