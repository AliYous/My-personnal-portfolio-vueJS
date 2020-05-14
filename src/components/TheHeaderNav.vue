<template>
    <div class="header-nav">

      <div class="logo">
        <h1 class="logo-text">ALI</h1>
      </div>

      <div class="nav-links">
          <v-btn text large>Mon portfolio</v-btn>
          <v-btn color="#6159CE" outlined rounded large>Travaillons ensemble</v-btn>
      </div>

    </div>
</template>

<script>
export default {
    name: 'TheHeaderNav'

}
</script>

<style scoped>
    .header-nav {
    height: 15vh;
    display: flex;
    justify-content: space-around;
    align-items: center;
    }
    .logo {

    }
    .nav-links {
    width: 25rem;
    display: flex;
    justify-content: space-around;
    }
</style>