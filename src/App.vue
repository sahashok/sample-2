<template>
  <v-app>
  <div>
    <!-- <h1>Welcome To vue js</h1> -->
    <!-- <SignUp /> -->
    <NavBar />
    <HomeCom />
    <!-- <NewOrbit /> -->
  </div>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  </v-app>
</template>

<script>
import HomeCom from './components/HomeCom.vue';
import NavBar from './components/NavBar.vue';
// import NewOrbit from './components/NewOrbit.vue';
// import SignUp from './components/SignUp.vue'
export default {
  name: 'App',
  components:{
    // SignUp,
    HomeCom,
    NavBar,
}

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>