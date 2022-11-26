<template>
  <div>
    <h3 class="version-app">Version 1.0.0</h3>
    <router-link to="/" class="router-link">Go Back</router-link>
  </div>
</template>

<script>
export default {
  name: 'About',
  inheritAttrs: false, // disable 'non-props' warning
};
</script>

<style scoped>
div {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  margin: 50px 0;
}
.router-link {
  text-decoration: none;
  color: steelblue;
}
.router-link:hover {
  color: red;
}
</style>
