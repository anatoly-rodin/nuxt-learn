<template>
  <section>
    <h1>User {{ $route.params.id }}</h1>
  </section>
</template>

<script>
export default {
  name: 'User',
  validate({ params }) {
    return /^\d+$/.test(params.id)
  }
}
</script>
