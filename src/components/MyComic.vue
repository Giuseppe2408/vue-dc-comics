<template>

        <div class="comic-card">
            <a href="">
                <img :src="details.thumb" :alt="details.series">
                <h4>{{details.series}}</h4>
            </a>           
        </div>
      
</template>

<script>
export default {
  name: 'MyComic',
  props : {
      details : Object,
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    
    .comic-card{
        flex-basis: 16%;
        margin-bottom: 50px;
        a{
            text-decoration: none;
            img {
                max-width: 100%;            
            }
            h4{
                font-size: 24px;
                color: white;
            }
        }
            
    }

</style>