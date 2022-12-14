<template>
<div>
  <!-- <h1>Feminine</h1> -->
  <div class="felirat">
    <img src="@/assets/felirat.png" alt="">
  </div>
 
<Footer/>




  <nav>
    <ul>
    <li><router-link to="/contact">Contact</router-link></li>
    <li><router-link to="/blog">Blog</router-link></li>
    <li><router-link to="/ceremonies">Ceremonies</router-link></li>
    <li><router-link to="/pregnancy">Pregnancy Yoga</router-link></li>
    <li><router-link to="/about">About</router-link></li>
    <li><router-link to="/">Home</router-link></li>
    


    </ul>
  </nav>
  <router-view/>
  </div>
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


@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital@1&display=swap');



img{
  border:0 none;
  height: 4rem;
  padding-bottom: 10px;
}


#app {
  font-family: 'Open Sans' ;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}



ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color:#F1D0E5
}

li {
  float: right;
}

li a {
  font-size: 20px;
  display: block;
  color: #89a864;
  font-weight:900;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color:#985277;
}
li a:focus {
    background-color:#985277;

}


</style>
