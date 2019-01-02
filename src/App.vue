<template>
  <div id="app">
    <Header></Header>
    <Conter></Conter>
  </div>
</template>

<script>
import Header from '@/assembly/header';
import Conter from '@/assembly/conter'
export default {
  components:{
    Header,
    Conter
  }
}
</script>

<style>
@import './common.css';
@media screen and (max-width: 1000px) {
    body {
      width: 100%;
      height: 100px;
      background-color:red
    }
}
</style>
