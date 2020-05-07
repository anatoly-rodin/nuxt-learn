<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <nuxt-link
      class="navbar-brand"
      to="/"
    >
      Nuxt SSR
    </nuxt-link>
    <div class="collapse navbar-collapse">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <nuxt-link
            class="nav-link"
            to="/"
            active-class="active"
            exact
            no-prefetch
          >
            Home
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link
            class="nav-link"
            to="/about"
            active-class="active"
          >
            About
          </nuxt-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>
