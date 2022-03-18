<template>
  <ul>
    <li>
      <router-link :to="{ name: 'home' }">Home</router-link>
    </li>
    <li>
      <router-link :to="{ name: 'about' }">About</router-link>
    </li>
    <li>
      <router-link :to="{ name: 'detail' }">Contact us</router-link>
    </li>
  </ul>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
ul {
  display: flex;
  background: #47a9cf;
  height: 70px;
  align-items: center;
  justify-content: center;
}
li {
  list-style: none;
  padding: 10px;
}
a {
  color: #ffffff;
  text-decoration: none;
}
</style>