<template>
  <div class="main">

    <!-- Header Navbar - 15vh-->
    <TheHeaderNav />

    <!-- Introduction with my photo and message - 85vh -->
    <Introduction />

    <!-- AboutMe - 40vh -->
    <AboutMe />

    <!-- My technos and languages - 60vh -->
    <Technologies />

    <!-- Portfolio - 100vh -->
    
  </div>
</template>

<script>
import TheHeaderNav from './components/TheHeaderNav';
import Introduction from './components/Introduction';
import AboutMe from './components/AboutMe';
import Technologies from './components/Technologies';

export default {
  name: 'App',

  components: {
    TheHeaderNav,
    Introduction,
    AboutMe,
    Technologies,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Jost:ital@1&display=swap');

.main {
 font-family: 'Jost', sans-serif;
 }

 .intro-container {
   display: flex;
   flex-direction: column;
   justify-content: flex-start;
   align-content: center;
   align-items: center;
   height: 80vh;
   margin-top: 5vh;
 }
 h2 {
   font-size: 42px;
 }
 p {
   font-size: 25px;
 }
 .paragraphs-container {
   text-align: center;
   width: 45%;
 }
 .image {
   margin-top: 5rem;
 }

 .scroll-down-btn {
   margin-top: 8rem;
 }
</style>
