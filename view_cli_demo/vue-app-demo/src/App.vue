<template>
  <div id="app">
    <img src="./assets/mayk.png" alt="Profile Picture" />
    <h1 style="color: #fff;">{{ msg }}</h1>
    <h3>Created by: Ronquillo, Michael Arnold</h3>

    <profile />
    <br>
    <education />
    <br>
    <skills />
    <br>
    <about-us />
  </div>
</template>

<script>
import Profile from './components/Profile.vue'
import Education from './components/Education.vue'
import Skills from './components/Skills.vue'
import AboutUs from './components/AboutUs.vue'

export default {
  name: 'App',
  components: {
    Profile,
    Education,
    Skills,
    AboutUs
  },
  data() {
    return {
      msg: 'The Main Component'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
  margin-top: 60px;
  background-color: black; 
  padding: 20px;
  width: 100%;
  box-shadow: 0 4px 8px teal;
}

h1, h2 {
  font-weight: normal;
}
h1{
  color: #fff;
}

img {
  border-radius: 50%;
  border: 5px solid teal; 
  background-color: #000;
  width: 150px;
  height: 150px;
}

h3 {
  margin-bottom: 40px;
  color: teal;
}

.profile,
.education,
.skills,
.about-us {
  margin-bottom: 30px;
}

div {
  text-align: left;
  margin: auto;
  max-width: 600px;
  background-color: e6f7ff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px teal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: red;
}
template{
  background-color: #000;
}
</style>
