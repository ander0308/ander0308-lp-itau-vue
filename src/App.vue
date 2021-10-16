<template>
  <div class="container">
      <header-component />
      <hero-component />
      <services-component />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import HeroComponent from './components/HeroComponent.vue'
import ServicesComponent from './components/ServicesComponent.vue'

export default {
  name: 'App',
  components: {
    'header-component' : HeaderComponent,
    'hero-component' : HeroComponent,
    'services-component' : ServicesComponent
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  list-style: none;

}
html{
  font-size: 62.5%;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  font-family: 'Roboto', sans-serif;
}
</style>
