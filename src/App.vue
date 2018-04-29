<template>
  <div id="app">
    <j-header></j-header>
     <router-view></router-view>
  </div>
</template>

<script>
import JHeader from "components/jd-head/jd-head"
export default {
  components:{
    JHeader
  }
}
</script>

<style>

</style>
