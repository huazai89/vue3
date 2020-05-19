<template>
  <section>
    <header>{{name + key +title}}</header>
    <footer>首页底部</footer>
  </section>
</template>

<script>
  export default {
    data() {
      return {
        title: 'home',
        name: 'my',
        key: '个人'
      }
    }
  }

</script>

<style>

</style>
