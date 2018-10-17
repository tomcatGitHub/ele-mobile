<template>
    <div class="home-container">
       <m-header></m-header>
    </div>
</template>
<script>
  import mHeader from '../../components/mHeader'
  export default{
    name:'home',
    components: {
      mHeader
    }
  }

</script>
<style lang="scss" scoped>
   .home-container{
     width: 100%;
     background: #eeeeef;
     overflow-y: hidden;
   }
</style>
