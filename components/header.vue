<template>
  <div>
    <h2>Header {{message}}</h2>
    <nuxt-link to="/">Back to /</nuxt-link>
  </div>
</template>

<script>
export default {
  props: ['message']
}
</script>
