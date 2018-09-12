<template>
<div id="footer3">
     
    <profile idd="profile2" source_file="./src/images/pic.jpg"/>
    <div class="header_input"><input type ="text"  class=" form-control" rows="3" placeholder="write something"></div>
    <div id="emoji"><icon iconname="fa fa-camera"/>
    <icon iconname="fa fa-smile-o"/></div>
    
</div>
</template>

<script>
import profile from "../BaseComponent/Profile.vue"
import icon from "../BaseComponent/LikeIcon.vue"
export default {
    name:'footer3',
  data () {
    return {
        
    }
  },
  components:{
 
    profile,icon
  }
 
 
}
</script>

<style>
#footer3{
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

#emoji{
margin-top:-6%;
float:right;
    display:inline-block;
left:-3.5%;
position:relative;
overflow:hidden;
}

</style>
