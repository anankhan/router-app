<template>
  <div class="about">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
  export default {
    name: 'About',
    data () {
      return {
        msg: 'This is very lightweight Frameworks and very useful to develop single page application'
      }
    }
  }
</script>
If you reload, you should now see a page like this.
<style scoped>
.about
{
    background-color: royalblue;
}
</style>
