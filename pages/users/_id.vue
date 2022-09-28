<template>
  <section>
    <h1>{{ message }}</h1>
    <p>id: {{ this.$route.params.id }}</p>
    <router-link to="/">return to index Page</router-link>
  </section>
</template>

<script>
export default {
  data: function () {
    return {
      message: '/users/_id.vue'
    }
  },
  validate({ params }) {
    return /^\d+$/.test(params.id)
  }
}
</script>
