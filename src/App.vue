<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>
      |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="stylus">
  html, body
    padding 0
    margin 0
    height 100%

  #app
    font-family Avenir, Helvetica, Arial, sans-serif
    -webkit-font-smoothing antialiased
    -moz-osx-font-smoothing grayscale
    text-align center
    color #2c3e50
    height 100%
    background #263238
    padding 0
    margin 0

  #nav {
    padding 10px

    a {
      color #F78C6C
    }
  }
</style>
