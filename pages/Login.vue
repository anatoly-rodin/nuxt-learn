<template>
  <section>
    <form>
      <div class="form-group">
        <label for="username">Username</label>
        <div class="input-group mb-3">
          <div class="input-group-prepend">
            <span
              id="basic-addon1"
              class="input-group-text"
            >
              @
            </span>
          </div>
          <input
            id="username"
            class="form-control"
            type="text"
            placeholder="Username"
            aria-label="Username"
            aria-describedby="basic-addon1"
          >
        </div>
      </div>
      <p>
        <nuxt-link to="/">
          To home page
        </nuxt-link>
      </p>
      <div class="form-group">
        <button
          class="btn btn-primary"
          type="submit"
        >
          Login
        </button>
      </div>
    </form>
  </section>
</template>

<script>
export default {
  name: 'Login'
}
</script>
