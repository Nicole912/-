
<template>
  <footer>
  <p>{{copyright}}</p></footer>
</template>
<script>
export default{
  name:"app-footer",
  data(){
    return{
      copyright:"Copy right 2017 Vue Demo"
    }
  }
}
</script>
<style scoped>
  footer{
    background:#222;
    padding:6px;
  }
 p{
    color:yellow;
    text-align:center;
  }
</style>
