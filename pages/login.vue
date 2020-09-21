<template>
<div>
    <nuxt-link to="town">
<v-icon dark left style="color:#000;">mdi-arrow-left</v-icon>
</nuxt-link>
    <div style="text-align: center;">    
       <h2 style="color:#cd853f;">Login</h2>
    </div>
    <br>
    <h1 style="color:#d69b61;">  Welcome Back! </h1>
     <v-form>
          <v-text-field v-model="user" label="Username"  />

          <v-text-field 
            :type="showPassword ? 'text' : 'password'" 
            v-model="password"
            label="Password"
            :append-icon="showPassword ? 'mdi-eye' : 'mdi-eye-off'"
            @click:append="showPassword = !showPassword"
          />
        </v-form>
        <br>
        <p style="color:#cd853f;"> Forget password ?</p>
        <br>
        <br>
        <nuxt-link to="map">
        <v-btn block rounded color="#cd853f">Log in</v-btn>
        </nuxt-link>
    </div>
</template>
<script>
export default {
    layout:"them2",
    data () {
    return {
      showPassword: false,
      gpa:'',
    }
},
}
</script>