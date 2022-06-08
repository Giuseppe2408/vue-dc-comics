<template>

    <section>
       <div>
           <ul>
               <li v-for="(item, i) in merchs" :key="i">
                   <a href="">
                       <img :src="item.src" alt="">
                       <span>{{item.text}}</span>                          
                       
                   </a>
               </li>
           </ul>
       </div> 
    </section>
      
</template>

<script>
export default {
  name: 'DcMerchandise',
  data(){
      return {
          merchs : [
              {
                  text : "DIGITAL COMICS",
                  src : require("../assets/img/buy-comics-digital-comics.png")
              },
              {
                  text : "DC MERCH",
                  src : require("../assets/img/buy-comics-merchandise.png")
              },
              {
                  text : "SUBSCRIPTION",
                  src : require("../assets/img/buy-comics-subscriptions.png")
              },
              {
                  text : "COMIC SHOP LOCALER",
                  src : require("../assets/img/buy-comics-shop-locator.png")
              },
              {
                  text : "DC POWER VISA",
                  src : require("../assets/img/buy-dc-power-visa.svg")
              },
          ]
      }
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    section {
        div{
            background-color: blue;
            height: 400px;
            display: flex;
            align-items: center;
            ul{
                display: flex;
                justify-content: space-around;
                li {
                    display: flex;
                    list-style-type: none;

                    a{
                        color: white;
                        text-decoration: none;
                        display: flex;
                        justify-content: space-between;
                        align-items: center;
                    }
                }
            }
        }
    }
</style>