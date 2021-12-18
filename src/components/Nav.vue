<template>
  <div class="nav">
  <img alt="Fees logo" src="./assets/logo.svg" class="logo">
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">Pitanja</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">Savjeti</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">Pretraga</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Nav',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav {
  height: 8vh;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  width: 140px;
  height: auto;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: blue;
}
</style>
