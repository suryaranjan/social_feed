<template>
<div id="footer2">
<div id="footer2_left">
    <icon iconname="em em---1" />
    <icon iconname="em em-heart" />
    <icon iconname="em em-astonished"/>
    <span>1.01M comments</span>
  </div>  
    <span id="footer2_right">Top Comments</span>
    
</div>
</template>

<script>
import icon from "../BaseComponent/LikeIcon.vue"
import profile from "../BaseComponent/Profile.vue"
export default {
    name:'footer2',
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
#footer2{
margin-top:10px;
clear:both;
overflow:hidden;
}
.fa {
    font-size: 24px;   
    color:grey;

    }
.profile{
  
  height:50px;
  width:50px;  
  float:right;

}
#footer2_right{
    float:right;
}
#footer2_left{
    float:left;
}

</style>
