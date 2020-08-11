<template>
  <v-container>
    <v-toolbar >
      <v-toolbar-title>KICK Products</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-xs-only" >
        <v-btn text>
          <router-link to="/">HOME</router-link>
        </v-btn>

        <v-btn>
          <router-link to="/about">ABOUT</router-link>
        </v-btn>

        <v-btn>
          <router-link to="/contact">CONTACT</router-link>
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>
  </v-container>
</template>

<script>
  export default {
    name: 'Header',

    data: () => ({
      
    }),
  }
</script>
