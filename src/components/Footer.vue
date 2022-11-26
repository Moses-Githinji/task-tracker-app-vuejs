<template>
  <footer>
    <p>Copyright &copy; 2022</p>
    <router-link to="/about" class="router-link">About</router-link>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
};
</script>

<style scoped>
a {
  color: #333;
}
.router-link {
  text-decoration: none;
  color: green;
}
footer {
  margin-top: 30px;
  text-align: center;
}
</style>
