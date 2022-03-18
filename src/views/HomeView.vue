<template>
  <div class="home">
    <div @click="makeRedirection">
      <p>Just click me for more details</p>
    </div>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {
  },
  methods: {
    makeRedirection() {
      this.$router.push({name:'detail'})
    }
  }
}
</script>

<style scoped>
  .home div {
    border: 1px solid #47a9cf;
    width: 30%;
    margin: 50px auto;
    padding: 10px;
  }
  .home div:hover {
    background: #47a9cf;
    color: #ffffff;
    border: #47a9cf;
    cursor: pointer;
  }
</style>