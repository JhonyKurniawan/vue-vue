<template>
  <div id="app">
    <router-view></router-view>
  </div>

  <h1> <center></center> </h1>
  <h2 align="center">Login ke Toko Baju</h2>

  <center>
    <label for="usname">Username:</label>
    <input type="text" id="usname" name="usname"><br><br>
    <label for="password">Pasworrd:</label>
    <input type="text" id="Password" name="Password"><br><br>
    <button type="button" class="btn btn-primary">Masuk</button>
  </center>
</template>

<script>
export default {
  name: "Login.vue"
}
</script>

<style scoped>

</style>