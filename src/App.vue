<template lang="pug">
  v-app
    v-toolbar
      v-toolbar-side-icon
      v-toolbar-title rettiwt
      v-spacer
      v-btn(icon to="/home")
        v-icon home
      // router-link(to="/search")
      //   v-btn(icon)
      //     v-icon search
      v-btn(icon to="/login")
        v-icon face
    v-content
      v-container(fluid fill-height)
        router-view
</template>

<style lang="stylus">
@import url('https://fonts.googleapis.com/icon?family=Material+Icons')

#app
  font-family: 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50

#nav
  padding: 30px

  a
    font-weight: bold
    color: #2c3e50

    &.router-link-exact-active
      color: #42b983
</style>
