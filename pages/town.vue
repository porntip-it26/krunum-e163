<template>
<div>
    <nuxt-link to="/">
<v-icon dark left style="color:#000;">mdi-arrow-left</v-icon>
</nuxt-link>
    <div style="text-align: center;">
    <v-container>
        <v-img src="images/3.png"></v-img>
        <h1 style="color:#cd853f;">Get the best coffee in town!</h1>
        <v-btn rounded color="#cd853f" dark>Register</v-btn>
        <nuxt-link to="login">
        <v-btn rounded class="ma-2" outlined color="#cd853f">
      Login</v-btn>
      </nuxt-link>
      <v-btn block rounded class="ma-2" outlined color="blue darken-1">
      Facebook</v-btn>
    </v-container>
    </div>
    </div>
</template>
<script>
export default {
    layout:"them3"
}
</script>