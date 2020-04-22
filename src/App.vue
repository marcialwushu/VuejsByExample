<template>
  <div id="app">
    <nav class="navbar is-transparent">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://bulma.io">MyCompany</a>
    <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
      <span></span>
      <span></span>
      <span></span>
    </div>
  </div>

  <div id="navbarExampleTransparentExample" class="navbar-menu">
    <div class="navbar-start">
      <div class="navbar-item has-dropdown is-hoverable"></div>
    </div>

    <div class="navbar-end">

    <router-link to="/" class="navbar-item">Home</router-link>
    <router-link to="/" class="navbar-item">Feature</router-link>
    <router-link to="/" class="navbar-item">About</router-link>
    <router-link to="/" class="navbar-item">FAQ</router-link>
      <div class="navbar-item">
        <div class="field is-grouped">

          <p class="control">
            <a class="button is-primary is-outlined" href="">
              <span class="icon">
                <i class="fas fa-download"></i>
              </span>
              <span>Join Now</span>
            </a>
          </p>
        </div>
      </div>
    </div>
  </div>
</nav>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="sass">
@import '../node_modules/bulma/bulma.sass'
@import 'mq'



</style>
