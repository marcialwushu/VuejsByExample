<template>
  <div class="home">
      <section class="hero">
        <div class="hero-body">
          <div class="container">
            <h1 class="title"> {{heading}} </h1>
            <div class="is-two-thirds column is-paddingless">
              <h2 class="subtitle is-4">{{ subheading }}</h2>
            </div>
            <a class="button is-large is-primary" id="learn">Learn More</a>
          </div>
        </div>
      </section>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      heading: 'Soaring to new heights',
      subheading: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla viverra felis eget maximus tincidunt.  '
    }
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
@import '../mq.sass'


.hero
  background: url('../assets/clouds.jpg')
  background-size: cover

  .title
    +mobile
      font-weight: bold

    +desktop
      font-size: 4rem
      margin-top: 2rem

h2
    margin: 1.5rem 02rem 0 !important

</style>
