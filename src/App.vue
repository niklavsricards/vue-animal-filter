<template>
  <Heading />
  <Filters />
  <Cards />
</template>

<script>
import Filters from './components/Filters.vue'
import Heading from "@/components/Heading";
import Cards from './components/Cards.vue';

export default {
  name: 'App',
  components: {
    Heading,
    Filters,
    Cards
  }
}
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }

</style>
