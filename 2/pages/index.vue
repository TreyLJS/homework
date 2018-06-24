<template>
  <section class="container">
    <div>
      <top-liblist></top-liblist>
      nuxt work
      <!-- <app-logo/>
      <h1 class="title">
        nuxt-test
      </h1>
      <h2 class="subtitle">
        a nuxt-test
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
      </div> -->
      <nuxt-link to="/home">Home</nuxt-link>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import TopLiblist from '~/components/common/top-liblist.vue'
// import SicHome from '~/'

export default {
  components: {
    AppLogo,
    TopLiblist
  }
}
</script>

<style>

</style>
