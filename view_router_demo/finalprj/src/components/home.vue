<template>
  <div class="home">
   
    <h1>Naruto</h1>
    <p>{{ msg }}</p>
    <img src="../assets/naruto.png" class="img-home">
    <p>NARUTO is a manga series created by Masashi
Kishimoto that was serialized in Weekly Shonen
Jump.
Met with immediate popularity following
its initial publication in 1999, the series went
on to receive an anime adaptation that
commenced broadcasting in 2002.

The manga concluded in 2014 with a total of 700 chapters.
The total number of print copies sold globally exceeds 250 million, and even now NARUTO events, games, merchandise,
and more continue to be created and released for fans to enjoy—
a testament to the series’ enduring influence and popularity
around the world.</p>
    
    
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'Welcome to My Home Page'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
  color: #42b983;
}
.img-home{
  width: 500px;
  margin-bottom: 2em;
}
</style>
