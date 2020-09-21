<template>
<div>
<nuxt-link to="login">
<v-icon dark left style="color:#000;">mdi-arrow-left</v-icon>
</nuxt-link>

    <v-img
      height="350" width="350"
      src="images/coffee.jpg"
    ></v-img>

    <v-card-title style="color:#d69b61;">Cafe Coffee
     
    </v-card-title>

 <v-icon style="color:#cd853f;">mdi-map-marker</v-icon><p style="color:#d69b61;"> 4.23 m    20 min</p>
 <nuxt-link to="menu">
        <v-btn block rounded color="#cd853f"> View Menu </v-btn>
        </nuxt-link>
        <br>
        <hr>
        <p style="color:#d69b61;">
Coffee
Factory
Ad·
4.6 
 (40) · Coffee Shop
Phuttamonthon Sai2
Open ⋅ Closes 6PM</p>
  
  </div>
</template>

<script>
  export default {
      layout:"them3",
    data: () => ({
      loading: false,
      selection: 1,
    }),

    methods: {
      reserve () {
        this.loading = true

        setTimeout(() => (this.loading = false), 2000)
      },
    },
  }
</script>