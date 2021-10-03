<template>
  <div>
    <h1>{{ msg }}</h1>
    <p>
      Kurumi 项目的前端页面，负责 Kindle 手动推送系统的页面控制。
    </p>
  </div>
</template>

<script>
export default {
  name: 'Kurumi Project',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
  color: #42b983;
}
</style>
