<template>
  <Navbar/>
  <Landing/>
  <About/>
  <Repos/>
  <Contact/>
  <Footer/>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Landing from './components/Landing.vue'
import About from './components/About.vue'
import Repos  from './components/Repos.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    Navbar,
    Landing,
    About,
    Repos,
    Contact,
    Footer,
},
  methods:{
    goto(refName)  {
      var element =  this.$refs[refName];
      var top = element.offsetTop;

      window.scrollTo(0, top);
    }
  }

}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

*,
*::before,
*::after{
  margin:0;
  padding: 0;
  box-sizing: border-box;
}
body,button,input,textarea{
  font-family: "Poppins", sans-serif;
}

</style>
