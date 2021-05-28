<template>
  <div class="container">
    <h1 class="heading">Vue Portfolio Challenge:</h1>
    <p>
      You work for a contracting business and have been paired up with a
      designer to build out a website for a hardware store.
    </p>
    <p>
      The owner of the store needs to be more competitive with big hardware
      companies by making their online shopping experience as pleasant as
      possible.
    </p>
    <p>
      Your task is to display hardware products for users to browse and
      purchase. You'll need to display all the products on a single page with
      key stats shown for each product. Additionally, the owner has requested
      that you be able to filter and sort these products.
    </p>
    <p>
      You've been given the freedom to use what tech stack that you want. Your
      team has been building out products in Vue so that is what has been
      stubbed out for you with the data available to get started.
    </p>
    <p>
      If you'd like a refresher on the challenge or want to look through designs
      to implement, visit the
      <a href="https://egghead.io/projects/the-beginner-s-guide-to-vue-3"
        >egghead challenge page</a
      >
    </p>
    <p>
      You'll also find design mock ups in /src/assets/ for you to reference as
      you work.
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
  <Dashboard />
</template>

<script>
import Dashboard from "./components/Dashboard.vue";

export default {
  name: "App",
  components: {
    Dashboard,
  },
};
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
