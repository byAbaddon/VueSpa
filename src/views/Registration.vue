<template>
  <div class="registration">
    <h2>Welcome to Registration</h2>

    <v-container class="fill-height" fluid>
      <v-row align="center" justify="center">
        <v-col cols="12" sm="8" md="4">
          <v-card class="elevation-12">
            <v-toolbar color="primary" dark flat>
              <v-toolbar-title>Login form</v-toolbar-title>
              <div class="flex-grow-1"></div>
            
            </v-toolbar>
            <v-card-text>
              <v-form>
                <v-text-field label="Login" name="login" prepend-icon="person" type="text"></v-text-field>

                <v-text-field
                  id="password"
                  label="Password"
                  name="password"
                  prepend-icon="lock"
                  type="password"
                ></v-text-field>
              </v-form>
            </v-card-text>
            <v-card-actions>
              <div class="flex-grow-1"></div>
              <v-btn color="primary">Login</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>

    <!-- <p>&copy; 2016 Flat Business Profile Widget. All rights reserved</p> -->
  </div>
</template>


<style scoped  lang="scss">
// @import url("https://fonts.googleapis.com/css?family=Oxygen");


// * {
//   margin: 0;
//   padding: 0;
// }

// .registration {
//   background: rgb(146, 112, 87);
//   background: cover;
//   font-family: "Oxygen", sans-serif;
//   text-align: center;
//   margin-top: 0em;
//   padding: 4.2%;
//   color: white;
// }
</style>

