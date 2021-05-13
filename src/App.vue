<template>
  <Header/>
  <Serve/>
  <House/>
 <Business/> 
</template>

<script>
import Header from './components/Header.vue'
import Serve from './components/Serve.vue'
 import House from './components/House.vue'
import Business from './components/Business.vue'

export default {
  name: 'App',
  components: {
    Header,
    Serve,
     Business,
     House
  }
}
</script>

<style>
.btn {
  margin-top: 80px;
}
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  overflow: hidden;
   overflow-y: auto;
  list-style: none;
}



a {
  text-decoration: none;
}
img {
  max-width: 100%;
}


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
