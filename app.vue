<template>
<div id="main">

  <component1/>
  <component2/>
  <container/>
  <footer1/>
    <footer2/>
  <footer3/>
</div>
</template>

<script>
import component1 from "./Src/Feed/HeaderComponent1.vue"
import component2 from "./Src/Feed/HeaderComponent2.vue"
import container from "./Src/Feed/Container.vue"
import footer1 from "./Src/Feed/Footer1.vue"
import footer3 from "./Src/Feed/Footer3.vue"
import footer2 from "./Src/Feed/Footer2.vue"
export default {
  data () {
    return {

    }
  },
  components:{
    component1,
    component2,
    container,
    footer1,
    footer3,
    footer2
  }
}
</script>

<style>
#main{
width:60%;
margin:auto;
}
</style>