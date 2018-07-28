<template>
  <div id="app">
      <app-message></app-message>
      <router-link to="/">Home</router-link>
    <router-link to="/Users/10">User 10</router-link>
    <router-link to="/Users/12">User 12</router-link>
     <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
