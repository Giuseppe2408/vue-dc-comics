<template>
    <section>
        <div>
            <img src="../assets/img/jumbotron.jpg" alt="">
        </div>
    </section>
      
</template>

<script>
export default {
  name: 'DcContent'
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    section{
        div{
            img {
                max-width: 100%;
                object-fit: contain;
            }
        }
    }
</style>