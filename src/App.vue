<template>
<Footer/>
<h1>Feminine to Thrive</h1>
  <nav>
    <ul>
    <li><router-link to="/contact">Contact</router-link></li>
    <li><router-link to="/about">Ceremonies</router-link></li>
    <li><router-link to="/pregnancy">Pregnency Yoga</router-link></li>
    <li><router-link to="/about">About</router-link></li>
    <li><router-link to="/">Home</router-link></li>
    


    </ul>
  </nav>
  <router-view/>
</template>


<script>
import Footer from '@/components/FooterBar.vue'



export default {
  name: 'App',
  components: {
    Footer
   
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

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color:#DDA0DD	
}

li {
  float: right;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
  background-color: #111;
}
</style>
