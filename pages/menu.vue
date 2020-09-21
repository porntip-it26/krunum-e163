<template>
    <div>
        <nuxt-link to="map">
<v-icon dark left style="color:#000;">mdi-arrow-left</v-icon>
</nuxt-link>
<div style="text-align: center;">
   <h1 style="color:#cd853f;" >MENU </h1>
   <hr>
   </div>
   
   <v-list three-line style="background-color:#ffffff;">
       <v-row>
           <v-col cols="6" md="2">
         <v-img src="images/44.png" width="40px"></v-img>
         <p style="color:#cd853f;" > ESPRESSO </p>
         </v-col>
     <br>
       <v-col cols="6" md="2">
         <v-img src="images/55.png" width="40px"></v-img>
        <p style="color:#cd853f;" > CHOCOLATE</p>
       </v-col>
      </v-row>
    <br>
    <v-row>
    <v-col cols="6" md="2">
         <v-img src="images/66.png" width="40px"></v-img>
        <p style="color:#cd853f;" > MOCHA </p>
    </v-col>
    <br>
    <v-col cols="6" md="2">
         <v-img src="images/77.png" width="40px"></v-img>
         <p style="color:#cd853f;" > LATTE </p>
    </v-col>
    </v-row>
   <br>
    <v-row>
        <v-col cols="6" md="2">
         <v-img src="images/88.png" width="40px"></v-img>
         <p style="color:#cd853f;" > MACCHIATO </p>
        </v-col>

        <v-col cols="6" md="2">
         <v-img src="images/88.png" width="40px"></v-img>
         <p style="color:#cd853f;" > MACCHIATO </p>
        </v-col>
      </v-row>


         <v-row>
    <v-col cols="6" md="2">
         <v-img src="images/66.png" width="40px"></v-img>
        <p style="color:#cd853f;" > MOCHA </p>
    </v-col>
    <br>
    <v-col cols="6" md="2">
         <v-img src="images/77.png" width="40px"></v-img>
         <p style="color:#cd853f;" > LATTE </p>
    </v-col>
    </v-row>
<br>
      <hr>  
    </v-list>
    <v-footer style="background-color:#ffffff;"> 
    <nuxt-link to="/">
      <v-icon style="color:#cd853f;">mdi-home</v-icon>  
    </nuxt-link>
<v-spacer></v-spacer>
    <nuxt-link to="town">
    <v-icon style="color:#cd853f;">mdi-history</v-icon>  
    </nuxt-link>
<v-spacer></v-spacer>
    <nuxt-link to="login">
      <v-icon style="color:#cd853f;">mdi-login</v-icon> 
   </nuxt-link>
<v-spacer></v-spacer>
   <nuxt-link to="map">
      <v-icon style="color:#cd853f;">mdi-send</v-icon>
    </nuxt-link>
<v-spacer></v-spacer>
    <nuxt-link to="menu">
      <v-icon style="color:#cd853f;">mdi-map-marker</v-icon>
      </nuxt-link>
</v-footer>
    </div>
</template>
<script>
export default {
    layout:"them3",
    data ()  {
        return {
        activeBtn: 1,
      }
    },
}
</script>