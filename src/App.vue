<template>
  <div id="app">
    <navbar/>
    <heading/>
    <sectionone/>
    <sectiontwo/>
    <sectionthree/>
    <lastsection/>
  </div>
</template>

<script>
import navbar from './components/navbar.vue'
import heading from './components/heading.vue'
import sectionone from './components/sectionone.vue'
import sectiontwo from './components/sectiontwo.vue'
import sectionthree from './components/sectionthree.vue'
import lastsection from './components/lastsection.vue'

export default {
  name: 'App',
  components: {
    navbar,
    heading,
    sectionone,
    sectiontwo,
    sectionthree,
    lastsection,
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Jost:wght@100;200;300;400;500;600;700;800;900&display=swap");
#app {
  font-family: "Jost", sans-serif;}

*{
  margin: 0;
  padding: 0;
}
</style>
