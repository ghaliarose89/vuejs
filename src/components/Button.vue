<template>
  <button :style="{background:color}"   @click="onclick()"  class="btn" >{{text}}</button>
</template>

<script>
export default {
    name:"Button",
    props:{
        text:String,
        color:String,
    },

methods:{
    onclick(){
        console.log("clciked")
    }
}
}
</script>

<style>

</style>