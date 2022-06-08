<template>
    <section>
        <div>
            <h1>content goes here</h1>
        </div>
    </section>
      
</template>

<script>
export default {
  name: 'DcContent',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    section{
        div{
            background-color: black;
            width: 100%;
            height: 300px;
            display: flex;
            justify-content: flex-start;
            h1 {
                color: white;
                font-size: 30px;
            }
        }
    }
</style>