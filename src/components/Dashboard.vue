<template>
  <div class="container">
    <p>Here is a dump of the data: </p>
    <pre>{{JSON.stringify(data, null, 2)}}</pre>
  </div>
</template>

<script>
import data from "../assets/data.json"
export default {
  name: 'Dashboard',
  data() {
    return {
      data
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
