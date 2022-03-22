<template>
<MyHeader></MyHeader>
<FirstSec></FirstSec>
<SecondSec></SecondSec>
<ThirdSec></ThirdSec>
<FourthSec></FourthSec>
<MyFooter></MyFooter>
</template>

<script>
 import MyHeader from "./MyHeader.vue"
 import FirstSec from "./FirstSec.vue"
import SecondSec from "./SecondSec.vue"
import ThirdSec from "./ThirdSec.vue"
import FourthSec from "./FourthSec.vue"
import MyFooter from "./MyFooter.vue"
export default {
name:"App",
components:{
  MyHeader,
  FirstSec,
  SecondSec,
  ThirdSec,
  FourthSec,
  MyFooter,
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
