<template>
  <div class="container">
    <h1 class="heading">Vue Portfolio Challenge: </h1>
    <p>
      You've been asked by the owner of a hardware store to present this point 
      of sales data in a more useful format. 
    </p>
    <p>Things you might want to consider:</p>
    <ul>
      <li>Filtering based on manufacturer;</li>
      <li>Filtering based on product type;</li>
      <li>Sorting based on price;</li>
      <li>Sorting based on quantity left;</li>
      <li>Styling changes if low/empty stock;</li>
    </ul>

  </div>
  <Dashboard/>
</template>

<script>
import Dashboard from './components/Dashboard.vue'

export default {
  name: 'App',
  components: {
    Dashboard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  margin: auto;
}

.heading {
  text-align: center;
}

.container {
  max-width: 800px;
  margin: auto;
}

</style>
