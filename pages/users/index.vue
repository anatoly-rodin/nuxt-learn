<template>
  <section>
    <h1>Users page</h1>
    <ul>
      <li
        v-for="user of 5"
        :key="user"
      >
        {{ user }}
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'Users'
}
</script>
