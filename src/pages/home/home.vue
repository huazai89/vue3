<template>
  <section>
    <header>{{name + title}}</header>
    <div>
      {{center}}
    </div>
    <footer>首页底部</footer>
  </section>
</template>

<script>
  export default {
    data() {
      return {
        title: 'home',
        name: 'my',
        center: '中间内容区'
      }
    }
  }

</script>

<style>

</style>
