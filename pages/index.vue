<template>
  <section class="container-fluid">
    <div>
      <navbar/>
      <app-logo/>
      <h1 class="title">
        Tugas PWA
      </h1>
      <h2 class="subtitle">
        PWA TheMealDB
      </h2>
    </div>
    <Categories/>
    <Meals/>
    <Area/>
    <Refs/>
    <p class="footer">&copy;2020 | Building with Nuxt.js</p>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import Navbar from '~/components/Navbar.vue'
import Area from '~/components/Area.vue'
import Categories from '~/components/Category.vue'
import Meals from '~/components/Meals.vue'

export default {
  components: {
    AppLogo,
    Navbar,
    Area,
    Categories,
    Meals
  }
}
</script>

<style>
.container-fluid {
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
  padding-bottom: 30px;
}

.links {
  padding-top: 15px;
}

.footer {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  margin-top: 100px;
  margin-bottom: 50px;
  color: #526488;
}
</style>

