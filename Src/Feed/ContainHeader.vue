<template>
<div id="header3">
    <profile idd="profile2" source_file="./src/images/pic.jpg"/>    
    <div id="heading">
       <p><b>Surya.net</b> changed their <i>cover photo</i></p>
        <icon iconname="fa fa-globe" status="2 mins"/>
    </div>

   
</div>
</template>

<script>
import profile from "../BaseComponent/Profile.vue"
import icon from "../BaseComponent/LikeIcon.vue"
export default {
    name:'containerHeader',
  data () {
    return {
        
    }
  },
  components:{
 
    profile,
    icon
  }
 
 
}
</script>

<style>
#header3
{
  margin-left:10px;
  margin-top:5px;
  overflow:hidden;  
}
#heading{
    display:inline-block;
    overflow:hidden;

}
#heading p{
    margin:0px;
}

</style>
