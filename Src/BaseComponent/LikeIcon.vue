<template>
  <div id="icon_container">
   <i id="icon" :class=iconname></i>
    <p id="icon_status">{{status}}</p>
  </div>
</template>

<script>
export default {
  name:"icon",

  data () {
    return {
         
    }
  },
  props:[
    'iconname',
    'status'
  ],  
}
</script>

<style>
#icon_container{
  display:inline;
  
  overflow:hidden;
  
margin-top:10px;
}
#icon{
 display:inline;
 float:left;
 
  padding:5px;
}
#icon_status{
  float:left;
  display:inline;
  padding:5px;
  margin:0px;
   
}
</style>
