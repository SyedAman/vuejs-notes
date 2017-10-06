<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        vuejs-notes
      </h1>
      <h2 class="subtitle">
        Taking notes of Vue.js to explore its features and learn. A studying notebook for people.
      </h2>
      <h3 class="author">
        — Syed Nashik Aman
      </h3>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation</a>
        <a href="https://github.com/SyedAman" target="_blank" class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.author {
  font-weight: 300;
  padding-bottom: 20px;
}

.links {
  padding-top: 15px;
}
</style>
