<template>
   <div class="contact">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
 name: 'Contact',
    data () {
      return {
        msg: 'Please contact TA for more assistance.'
      }
    }
}
</script>

<style scoped>
.contact
{
background-color: aqua;
}
</style>