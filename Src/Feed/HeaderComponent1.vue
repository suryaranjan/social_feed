<template>
<div id="header1">
    <icon iconname="fa fa-edit" status="status"/>
    <icon iconname="fa fa-camera-retro" status="Photo/Video"/>
    
    <profile idd="profile" source_file="./src/images/pic.jpg"/>
</div>
</template>

<script>
import icon from "../BaseComponent/LikeIcon.vue"
import profile from "../BaseComponent/Profile.vue"
export default {
    name:'component1',
  data () {
    return {
        
    }
  },
  components:{
    icon,
    profile
  }
 
 
}
</script>

<style>

.fa {
    font-size: 24px;   
    color:grey;

    }
.profile{
  
  height:50px;
  width:50px;  
  float:right;

}
#header1{
  
  overflow:hidden;
  margin:0px;
}

</style>
