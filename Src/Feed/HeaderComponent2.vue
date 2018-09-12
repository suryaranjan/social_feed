<template>
<div class="header2 container">
     
    <profile idd="profile2" source_file="./src/images/pic.jpg"/>
    <div class=" header_input"><input type ="text"  class="form-control" rows="5" placeholder="write something"></div>
</div>
</template>

<script>
import profile from "../BaseComponent/Profile.vue"
export default {
    name:'component2',
  data () {
    return {
        
    }
  },
  components:{
 
    profile
  }
 
 
}
</script>

<style>
.header2{
   width:100%;
    margin-top:5px;
   overflow:hidden;
    
     
}
.profile2{
    width:5%;
    float:left;
    height:50px;
    width:50px;
   
    margin-top:10px;
    display:inline-block;

}
.header_input input
{
   
    width:85%;
    display:inline-block;
    margin-top:-10px;
    margin-left:10px;
}


</style>
