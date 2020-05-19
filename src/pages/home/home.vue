<template>
  <section>
    <header>{{name + key +title}}</header>
    <div>
      我的中间测试区域
    </div>
    <div>{{center}}</div>
    <footer>首页底部</footer>
  </section>
</template>

<script>
  export default {
    data() {
      return {
        title: 'home',
        name: 'my',
        key: '个人',
        center: '我的中间内容测试区'
      }
    }
  }

</script>

<style>

</style>
