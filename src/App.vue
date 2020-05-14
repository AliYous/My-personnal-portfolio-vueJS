<template>
  <div class="main">

    <!-- Header Navbar -->
    <TheHeaderNav />
    
  </div>
</template>

<script>
import TheHeaderNav from './components/TheHeaderNav'
export default {
  name: 'App',

  components: {
    TheHeaderNav
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
 color: #6159CE;
}
</style>
