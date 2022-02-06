<template>
  <div>
    <!-- ***** Preloader Start ***** -->
    <div id="preloader">
        <div class="jumper">
            <div></div>
            <div></div>
            <div></div>
        </div>
    </div>
    <!-- ***** Preloader End ***** -->
    <!-- ***** Header Area Start ***** -->
        <Header/>
    <!-- ***** Header Area End ***** -->


    <!-- ***** Welcome Area Start ***** -->
        <Welcome/>
    <!-- ***** Welcome Area End ***** -->

    <!-- ***** Features Big Item Start ***** -->
        <About/>
    <!-- ***** Features Big Item End ***** -->

    <div class="left-image-decor"></div>

    <!-- ***** Features Big Item Start ***** -->
        <Promotion/>
    <!-- ***** Features Big Item End ***** -->

    <div class="right-image-decor"></div>

    <!-- ***** Testimonials Starts ***** -->
        <Testimonials/>
    <!-- ***** Testimonials Ends ***** -->


    <!-- ***** Footer Start ***** -->
    <Footer/>
  </div>
</template>

<script>
import Header from './Components/Header'
import Welcome from './Components/Welcome'
import About from './Components/About'
import Promotion from './Components/Promotion'
import Testimonials from './Components/Testimonials'
import Footer from './Components/Footer'
export default {
  name: 'HelloWorld',
  components: {
    // HelloWorld
    Header,Welcome,About,Promotion,Footer,Testimonials
  }
//   props: {
//     msg: String
//   }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    /* h3 {
    margin: 40px 0 0;
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
    } */
</style>
