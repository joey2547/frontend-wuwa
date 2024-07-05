<template>
    <v-app>
      <v-main>
        <v-container class="d-flex justify-center align-center fill-height">
          <v-card class="pa-5 rounded-card" max-width="600">
            <v-card-title class="text-h5 text-center">Sign Up</v-card-title>
            <v-card-text>
              <v-form>
                <v-text-field
                  label="Email"
                  v-model="email"
                  prepend-icon="mdi-email"
                  class="rounded-input"
                  outlined
                  dense
                  hide-details
                ></v-text-field>
                <v-text-field
                  label="Password"
                  v-model="password"
                  type="password"
                  prepend-icon="mdi-lock"
                  class="rounded-input"
                  outlined
                  dense
                  hide-details
                ></v-text-field>
                <v-text-field
                  label="Re-entry Password"
                  v-model="password"
                  type="password"
                  prepend-icon="mdi-lock"
                  class="rounded-input"
                  outlined
                  dense
                  hide-details
                ></v-text-field>
                <div class="text-center my-3">  </div>
                <v-btn class="w-100 rounded-btn secondary-btn" @click="signUp">SIGN UP</v-btn>
              </v-form>
            </v-card-text>
          </v-card>
        </v-container>
      </v-main>
    </v-app>
  </template>
  
  <script>
  export default {
    data() {
      return {
        email: '',
        password: '',
      };
    },
    methods: {

      signUp() {
        // Handle sign up
        console.log('Sign Up', this.email, this.password);
      },
    },
  };
  </script>
  
  <style scoped>
  @import 'bootstrap/dist/css/bootstrap.min.css';
  
  /* General styles */
  .v-card {
  border-radius: 25px;
  background-color: #dcceaf; /* Light beige background to match the image */
  width: 400px; /* Adjust width as per your requirement */
  height: 320px; /* Adjust height as per your requirement */
  }
  
  .v-card-title {
    color: #5d4037; /* Dark brown colour */
  }
  
  .v-card-text {
    padding: 0;
  }
  
  .v-container {
    padding: 0;
  }
  
  .v-main {
    background-color: #0575b7; /* Background colour to match the image */
  }
  
  /* Input field styles */
  .v-text-field--outlined .v-input__control {
    border-radius: 25px;
  }
  
  .rounded-input .v-input__control {
    border-radius: 25px;
  }
  
  /* Button styles */
  .v-btn {
    border-radius: 25px;
    font-weight: bold;
  }
  
  .secondary-btn {
    background-color: #ffb300; /* Orange button colour */
    color: white;
  }
  
  .rounded-btn {
    border-radius: 25px;
  }
  
  .text-center {
    text-align: center;
  }
  
  .my-3 {
  margin-top: 1rem;
  margin-bottom: 1rem;
  font-size: 1rem;
  color: #7f6e49; 
  }
  </style>
  