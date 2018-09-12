<template>
<div id="fooetr1">
    <icon iconname="fa fa-thumbs-up" status="Likes"/>
    <icon iconname="fa fa-comments-o" status="comments"/>
    <icon iconname="fa fa-share-alt" status="share"/>
    
    <profile idd="profile" source_file="./src/images/pic.jpg"/>
</div>
</template>

<script>
import icon from "../BaseComponent/LikeIcon.vue"
import profile from "../BaseComponent/Profile.vue"
export default {
    name:'footer1',
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
#footer1{
margin-top:10px;}
.fa {
    font-size: 24px;   
    color:grey;

    }
.profile{
  
  height:50px;
  width:50px;  
  float:right;

}
#footer{
  background-color:green;
  overflow:hidden;
  margin:0px;
}

</style>
