<template>
  <div id="app">
    <Header/>
    <router-view></router-view>  
  </div>
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  components: {
    Header    
  }
}
</script>


<style>
body {
  margin: 0px;
  font-family: "Avenir", Arial, Helvetica, sans-serif;
  color: #234;
}

ul{
  list-style: none;
  padding: 0px;
  margin: 0px;
}

a {
  font-weight: bold;
  text-decoration: none;
  color: #234;
}

a.router-link-exact-active {
  color: #4b8;
}
</style>
