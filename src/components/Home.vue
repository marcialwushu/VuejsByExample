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

      <section class="section">
        <div class="container">
          <div class="columns pd is-desktop">
            <div class="column is-1 has-text-centered">
              <i class="fa fa-cog is-primary"></i>
            </div>
            <div class="column is-one-third-desktop">
              <p class="title"><strong>We provide superiorlogistics so that your business can succeed in a crazy world.</strong></p>
            </div>
            <div class="column ">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla viverra felis eget maximus tincidunt.Phasellus vitae dolor nec neque vehicula luctus eu eu nisi.</p>
            </div>
          </div>
        </div>

        <div class="columns pd">
          <div class="column">
            <div class="card">
              <div class="card-content">
                <p class="title">I think it's an absolutely excellent tool for our business. I can't survive without this</p>
                <p class="subtitle">- Gary Simon</p>
              </div>
            </div>
          </div>
          <div class="column">
            <div class="card">
              <div class="card-content">
                <p class="title">I think it's an absolutely excellent tool for our business. I can't survive without this</p>
                <p class="subtitle">- Gary Simon</p>
              </div>
            </div>
          </div>
          <div class="column">
            <div class="card">
              <div class="card-content">
                <p class="title">I think it's an absolutely excellent tool for our business. I can't survive without this</p>
                <p class="subtitle">- Gary Simon</p>
              </div>
            </div>
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

.fa-cog
  font-size: 40px

#learn
  +desktop
    margin-bottom: 2rem


</style>
