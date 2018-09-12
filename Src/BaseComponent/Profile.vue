<template>
    <div class="imga">
        <img :src=source_file :class=idd>
        
    </div>
</template>
<script>
export default{
    name:"profile",
    data(){
        return{

        }
    },
    props:[ 'source_file', 'idd']
       
    
}
</script>
<style>
.imga{
    display:inline;
    overflow:hidden;
    padding:10px;
}
</style>