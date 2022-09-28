<template>
  <section class="container">
    <h2>thist is a index page.</h2>
    <p>{{ message }}</p>
    <hr>
    <ul>
      <li>
        <router-link to="/users/">user Page</router-link>
      </li>
      <li>
        <router-link to="/users/1">user_id=1 Page</router-link>
      </li>
      <li>
        <router-link to="/price">Price Page</router-link>
      </li>
      <li>
        <router-link to="/mypage">myPage</router-link>
      </li>
    </ul>
  </section>
</template>

<script>
// const axios = require('axios')
// let url = '

export default {
  name: 'IndexPage',
  data: function(){
    return {
      message: 'Hello !'
    }
  }
}
</script>

<style>
h2 {
  font-family: 'Permanent Marker', cursive;
}
</style>
