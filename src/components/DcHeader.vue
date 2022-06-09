<template>
  <header>
      <img src="../assets/img/dc-logo.png" alt="logo dc comics">
      <nav>
          <ul>
              <li v-for="(link, i) in links" :key="i">
                  <a  href=""
                  :class="link.current ? 'here' : ''">
                      {{link.text}}
                  </a>
              </li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {
  name: 'DcHeader',
  data(){
      return{
          links : [
            {
                text : "CHARACTERS",
                url : "#",
                current : false,           
            },
            {
                text : "COMICS",
                url : "#",
                current : true,           
            },
            {
                text : "MOVIES",
                url : "#",
                current : false,           
            },
            {
                text : "TV",
                url : "#",
                current : false,           
            },
            {
                text : "GAMES",
                url : "#",
                current : false,           
            },
            {
                text : "COLLECTIBLES",
                url : "#",
                current : false,           
            },
            {
                text : "VIDEOS",
                url : "#",
                current : false,           
            },
            {
                text : "FANS",
                url : "#",
                current : false,           
            },
            {
                text : "NEWS",
                url : "#",
                current : false,           
            },
            {
                text : "SHOP",
                url : "#",
                current : false,           
            },
          ],
      }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    header {
        display: flex;
        justify-content: space-around;
        align-items: center;
        

        img {
            width: 100px;
            height: 100px;
            object-fit: contain;
        }

        ul{
            display: flex;
            justify-content: flex-end;
            
            li {
                list-style-type: none;              
                a {
                    padding: 10px;
                    text-decoration: none;
                    color: black;

                    &:hover{
                        color: blue;
                    }
                    
                    &.here{
                        border-bottom: 1px solid blue;
                    }
                }
            }
            
        }



    }
</style>
