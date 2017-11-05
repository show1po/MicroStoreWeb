<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
      <br>
      <li><a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a></li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
<!--var vue = new Vue ({-->
<!--el: '#app', //網頁最外層的 id，所有 vue 操控的部分，皆要寫在裡面-->
<!--data: {-->
<!--//網頁用到的資料都放在這-->
<!--},-->
<!--created: function () {-->
<!--// 網頁載入完成，先執行的 function 內容寫在這(像 jQ 的 .ready())-->
<!--this.$http.post('/api/getAllMenu').then((response) => {-->
<!--/* 成功拿到資料，然後... */-->
<!--alert(response);-->
<!--}, (response) => {-->
<!--/* 失敗，發生錯誤，然後...*/-->
<!--});-->
<!--},-->
<!--methods: {-->
<!--//各種要用的 function 寫在這-->
<!--},-->
<!--computed: {-->
<!--//計算屬性，好用，但此範例沒用到 XDD-->
<!--}-->
<!--});-->
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
