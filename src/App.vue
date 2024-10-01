<template>
  <div class="wrapper">
    <Navbar/>
    <Header/>
    <AboutMe/>
    <MyWorks/>
    <Footer/>
  </div>
</template>

<script>

import Navbar from "./components/Navbar";
import Header from "./components/Header";
import AboutMe from "./components/AboutMe";
import MyWorks from "./components/MyWorks";
import Footer from "./components/Footer.vue";


export default {
  components: {
    Navbar,
    Header,
    AboutMe,
    MyWorks,
    Footer
  }
}

</script>