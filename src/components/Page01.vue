<template>
<div>
  <v-app-bar class="bg-cyan-darken-1 text-white">
    <v-app-bar-nav-icon variant="text" @click="drawer = !drawer"/>
    <v-toolbar-title>Vuetify Practice</v-toolbar-title>

    <v-spacer></v-spacer>

    <v-btn variant="text" icon="mdi-magnify"></v-btn>
    <v-btn variant="text" icon="mdi-filter"></v-btn>
    <v-btn variant="text" icon="mdi-dots-vertical"></v-btn>
  </v-app-bar>

  <v-navigation-drawer v-model="drawer" temporary>
    <v-list :items="items"></v-list>
  </v-navigation-drawer>

</div>
</template>

<script>
export default {
  name: 'Page01',
  data: () => ({
    drawer: null,
    items: [
      { title:'HOME', value:'home' },
      { title:'COMPANY', value:'company' }
    ],
  })
}
</script>
