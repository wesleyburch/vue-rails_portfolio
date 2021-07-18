<template>
  <div id="app">
    <Navigation />
		<div class="mt-3"></div>
		<router-view />
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
// import Portfolio from './views/Portfolio.vue'

export default {
	name: 'App',
	components: {
		Navigation
	}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
