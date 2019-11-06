<template>
  <div>
    <v-app-bar dark>
      <v-btn>menu</v-btn>
      <v-spacer></v-spacer>
      <v-icon>mdi-anchor</v-icon>&nbsp;
      <v-toolbar-title ml-12>VUE-SPA WEB PROJECT</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn>sign in</v-btn>&nbsp;
      <v-btn router-link to="/registration">
        join &nbsp;
        <v-icon>mdi-heart</v-icon>
      </v-btn>
    </v-app-bar>

    <router-view />
  </div>
</template>





<script>
export default {};
</script>

