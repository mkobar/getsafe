<template>
  <div class="hello">
    <img class="logo center-align" src="../assets/logo.svg" alt="Logo">
    <h1 class="title center-align">GetSafe</h1>
    <router-link class="waves-effect waves-light btn-large light-blue darken-4" to="/manager/login">
      Manager
    </router-link>
    <br />
    <router-link class="waves-effect waves-light btn-large light-blue darken-4" to="/customer">
      Customer
    </router-link>
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .logo{
    display: block;
    margin: auto;
    margin-top: 3.5rem;
    margin-bottom: .5rem;
  }

  .title{
    margin-top: 0;
    margin-bottom: 5rem;
    font-size: 2rem;
    color: #2FA2D4;
  }

  .btn-large{
    display: block;
    width: 60%;
    margin: auto;
    margin-bottom: .5rem;
  }
</style>
