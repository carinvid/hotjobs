<template>
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link :to= "{ name:'About'}">About</router-link>
    <router-link :to= "{ name: 'Jobs'}">Jobs</router-link>
  </div>
  <router-view/>
</template>

<script>


</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}

#nav {
  padding: 30px;
}

#nav a {
  font-size: bold;
  color: rgb(8, 70, 70);
  text-decoration: none;
  padding: 10px;
  border-radius:4px ;
}

#nav a.router-link-exact-active {
  color: white;
  background: rgb(204, 41, 68);
}
</style>
