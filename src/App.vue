<template>
  <v-app id="data">
    <v-app-bar app dense flat outlined>
      <v-tabs class="navbar-class">
        <v-tab to="/" style="color:white;">Home</v-tab>
        <v-tab to="/products" style="color:white;">Products</v-tab>
        <v-tab to="/cart" style="color:white;">Cart</v-tab>
      </v-tabs>
    </v-app-bar>

    <v-main>
      <v-container>
        <router-view />
      </v-container>
    </v-main>
  </v-app>
</template>
<style lang="css">
  #data{
    background-color:black;
    color:white;
  }
  .navbar-class{
    background-color:black;
  }
  .navbar-class-0{
     color:white ;
  }
</style>