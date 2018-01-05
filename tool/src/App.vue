<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
  body{
    margin:0;
    background-color:#f0f4f7;
  }
ul,li{
  padding:0;
  list-style:none;
}
li{
  height:30px;
  line-height:30px;
}
a{
  text-decoration: none;
}
.container{
  padding:0 40px;
}
.card{
  margin:17px;
  border:1px solid #dfebf9;
  border-radius: 8px;
  background-color:#fff;
  padding:30px 40px;
  box-sizing: border-box;
}
.card .title{
  font-size:26px;
  color:rgb(146,157,171);
}
.btn{
  display:inline-block;
  width:100%;
  background-color:#ccc;
  color:#fff;
  padding:10px 0;
  text-align: center;
  border-radius: 5px;
  margin:9px 0;
}
.danger{
  background-color:#fd5561;
}
.success{
  background-color:#0b7cff;
}
</style>
