<template>
<div id="container">
     <containerHeader/>
    <div id="contain">
       <profile idd="back" source_file="./src/images/trim.jpg"/>  
    </div>
</div>
</template>

<script>
import containerHeader from "../Feed/ContainHeader.vue"
import profile from "../BaseComponent/Profile.vue"
export default {
    name:'container',
  data () {
    return {
        
    }
  },
  components:{
   containerHeader,
   profile
    
  }
 
 
}
</script>

<style>
#container{
width:100%;
}
#contain .imga img
{
    width:100%;
}
#back{
    height:30%;
}


</style>
