<template>
  <div id="app">
    <div class="top-nav">
      <h2 class="logo">

      </h2>
      <div class="nav-links">
        <v-btn flat>Mon travail</v-btn>
        <v-btn outlined x-large>Travaillons ensemble !</v-btn>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Jost:ital,wght@1,300&display=swap');

#app {
  font-family: Jost, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
