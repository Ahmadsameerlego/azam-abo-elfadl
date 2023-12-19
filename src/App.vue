<template>
  <router-view/>
  <router-link to="/notification">
    <Toast />
  </router-link>
  
</template>

<script>

  export default{
    data(){
      return{

      }
    },
    methods:{
       
      },
      components:{
        
      },
     mounted(){ 
      
    },
    // created(){
    //   localStorage.clear();
    // }
  }
</script>
<style lang="scss">

</style>