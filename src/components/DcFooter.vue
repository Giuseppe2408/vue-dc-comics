<template>

    <footer>
      
      <MyList/>

      <div id="img">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
      
      

      <UnderFooter/>
      
      
    </footer>
      
</template>

<script>
import UnderFooter from './UnderFooter.vue';
import MyList from './MyList.vue';

export default {
  name: 'DcFooter',

  components : {
    UnderFooter,
    MyList
  }
  
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    footer {
      background-image: url(../assets/img/footer-bg.jpg);
      background-size: contain;
      
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      align-items: center;
    
      
    }
</style>