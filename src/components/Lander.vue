<template>
  <div class="lander">
      <div class="col-md-auto"> <!-- col-6 align-self-center,col-md-auto -->
      <div class="pictures">
    <img alt="Vue logo"  class="rounded-circle center-block" 
src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Woman_1.jpg/220px-Woman_1.jpg">
<h1> Jordyn Blakey </h1>
<p> Computer Programmer</p>
<h2> This website is a little about me! </h2>
<h2> I hope you enjoy </h2>
</div>
</div>

  
</div>

</template>

<script>
export default {
  name: 'Lander',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p,h1 {
  padding: 40px 0 0;
}
.lander {

  align-content: center;
  padding-top: 10%;
  padding-bottom: 10%;
  background-color:#DADED4;
}

.phrase {
  background-color: red;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}



img {
  padding:200;
  align-content: center;
 
}
</style>
