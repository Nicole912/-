<template>
  <div id="app">
<h1>{{title}}</h1>
    <app-header></app-header>
    <users></users>
    <app-footer></app-footer>
  </div>
</template>

<script>
  import Users from './Components/Users'
import Header from './Components/Header'
import Footer from './Components/Footer'
export default {
  name: 'App',
  data () {
    return{
      title:"这是我的第一个VUE脚手架项目"
    }
  },
components:{
    'users':Users, //'users':可以省略
'app-header':Header,
  "app-footer":Footer
}
}

</script>

<style>
h1 {
color:purple;
}
</style>
