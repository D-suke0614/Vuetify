<template>
  <v-app>
    <!-- <v-app-bar class="light-blue lighten-2 white--text text-sm-h4">
      <v-app-bar-nav-icon class="white--text" variant="text" @click="drawer = !drawer"/>
      <v-toolbar-title>Vuetify Practice</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn variant="text" icon="mdi-magnify"></v-btn>
      <v-btn variant="text" icon="mdi-filter"></v-btn>
      <v-btn variant="text" icon="mdi-dots-vertical"></v-btn>
    </v-app-bar> -->

    <!-- <v-navigation-drawer v-model="drawer" temporary absolute>
      <v-list-item-group v-model="group" active-class="light-blue lighten-5 text--accent-4">
          <v-list-item>
            <v-list-item-title>Foo</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>Bar</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>Fizz</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>Buzz</v-list-item-title>
          </v-list-item>
        </v-list-item-group>
    </v-navigation-drawer> -->
      <!-- <Page01 /> -->
      <!-- <HelloWorld /> -->
      <v-main>
        <!-- <Calender /> -->
        <Axios />
      </v-main>
  </v-app>

</template>

<script>
import HelloWorld from './components/HelloWorld';
import Page01 from './components/Page01';
import Calender from './components/Calender.vue'
import Axios from './components/Axios-pra.vue'

export default {
  name: 'App',

  components: {
    Page01,
    HelloWorld,
    Calender,
    Axios
  },

  data: () => ({
    drawer: null,
  }),
};
</script>
