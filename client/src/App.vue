<template>
  <v-app>
    <v-navigation-drawer app color="secondary">
      <v-container>
        <!-- <v-img
        outlined
        max-height="400"
        src=""        
        ></v-img>-->
        <v-img
        outlined
        max-height="400"
        src="https://0.soompi.io/wp-content/uploads/2022/05/02081143/TWICE-Taste-of-Love.jpg"        
        ></v-img>
        <v-spacer></v-spacer>
        <v-btn
          depressed
          color="primary"
          :to="{name: 'Ordenes'}"
          width="100%"
          class="mt-5"

        >
          <v-icon class="mx-3">
            fas fa-concierge-bell
          </v-icon>
            Órdenes
        </v-btn>      
        <v-spacer></v-spacer>
        <v-btn
          depressed
          color="primary"
          :to="{name: 'Meseros'}"
          width="100%"
          class="mt-5"
        >
          <v-icon class="mx-3">
            fas fa-users
          </v-icon>
          Meseros
        </v-btn> 
        <v-spacer></v-spacer>                    
        <v-btn
          depressed
          color="primary"
          :to="{name: 'Comidas'}"
          width="100%"
          class="mt-5"
        >
          <v-icon class="mx-3">
            fas fa-utensils
          </v-icon>
          Comidas
        </v-btn>      
        <v-spacer></v-spacer>
        <v-btn
          depressed
          color="primary"
          :to="{name: 'Bebidas'}"
          width="100%"
          class="mt-5"
        >
          <v-icon class="mx-3">
            fas fa-cocktail
          </v-icon>
            Bebidas
        </v-btn>      
        <v-spacer></v-spacer>
        <v-btn
          depressed
          color="primary"
          :to="{name: 'Mesas'}"
          width="100%"
          class="mt-5"
        >
          <v-icon class="mx-3">
            fas fa-chair
          </v-icon>
            Mesas
        </v-btn> 
        <v-spacer></v-spacer>
        <v-btn
          depressed
          color="primary"
          :to="{name: 'Consultas'}"
          width="100%"
          class="mt-5"
        >
          <v-icon class="mx-3">
            fas fa-database
          </v-icon>
            Consultas
        </v-btn> 
    </v-container>
  </v-navigation-drawer>

  <v-app-bar app color="primary" dark>
    <v-row class="my-5"> <!--mx= en x / mt= arriba / my= en y-->
      <v-icon class="mx-5" x-large>
        fas fa-torii-gate
      </v-icon>
      <h2>PROYECTO FINAL</h2>
    </v-row>
  </v-app-bar>

  <!-- Sizes your content based upon application components -->
  <v-main>

    <!-- Provides the application the proper gutter -->
    <v-container fluid>

      <!-- If using vue-router -->
      <router-view></router-view>
    </v-container>
  </v-main>

  <v-footer app>
    <!-- -->
  </v-footer>
</v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>


