<template>
  <section>
    <h1>Users page</h1>
    <ul>
      <li
        v-for="user of 5"
        :key="user"
      >
        <a
          href="#"
          @click.prevent="openUser(user)"
        >
          User {{ user }}
        </a>
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'Users',
  methods: {
    openUser(id) {
      this.$router.push(`/users/${id}`)
    }
  }
}
</script>
