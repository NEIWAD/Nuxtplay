<template>
  <section class="hero is-success is-fullheight">
  <div class="hero-body">
    <div class="container">
      <h1 class="title">
        Nuxtplay
      </h1>
      <h2 class="subtitle">
        My little playground to test Nuxt
      </h2>
      <nuxt-link to="/home">
        <button class="button is-info">Let's do this !</button>
      </nuxt-link>
    </div>
  </div>
</section>
</template>

<script>
export default {
  layout: 'noNav'
}
</script>
