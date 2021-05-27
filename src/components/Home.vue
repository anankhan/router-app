<template>
  <div class="home">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
  export default {
    name: 'Home',
    data () {
      return {
        msg: 'We are developing Vue.js Project '
      }
    }
  }
</script>
If you reload, you should now see a page like this.
<style scoped>
.home
{
  background-color: red;
}
</style>
