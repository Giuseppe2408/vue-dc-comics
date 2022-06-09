<template>
    <section>
        <div>
            <button>
                <span>CURRENT SERIES</span>
            </button>
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
            width: 100%;
            height: 1070px;
            background-image: url(../assets/img/jumbotron.jpg);
            background-size: contain;
            button{
                background-color: blue;
                border: 1px solid blue;
                margin-top: 1030px;
                width: 300px;
                padding: 30px;
                align-self: flex-end;
                span{
                    color: white;
                    font-size: 30px;
                }
            }
        }

        
    }
</style>