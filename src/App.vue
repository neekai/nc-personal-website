<template>
  <div id="app">
    <Header />
    <router-view/>
  </div>
</template>


<script>
import Header from './components/layout/Header';


export default {
  name: "app",
  components: {
    Header,
  }
}

</script>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

body {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #f4f4f4;
}

@import url('https://fonts.googleapis.com/css?family=Open+Sans|Roboto');


</style>
