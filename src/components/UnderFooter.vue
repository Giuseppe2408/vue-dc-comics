<template>

    <div id="contacts">
        <div>
          <button>
              <span>SIGN UP</span>
          </button>
        </div>
        <div>
          <ul id="social">
            <li>
              <a href="">
                <h2>FOLLOW US</h2>
              </a>
            </li>
            <li>
              <a href="">
                <img src="../assets/img/footer-facebook.png">
              </a>
            </li>
            <li>
              <a href="">
                <img src="../assets/img/footer-youtube.png">
              </a>
            </li>
            <li>
              <a href="">
                <img src="../assets/img/footer-periscope.png">
              </a>
            </li>
            <li>
              <a href="">
                <img src="../assets/img/footer-pinterest.png">
              </a>
            </li>
            <li>
              <a href="">
                <img src="../assets/img/footer-twitter.png">
              </a>
            </li>
          </ul>
        </div>
    </div>

        
      
</template>

<script>
export default {
  name: 'UnderFooter', 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    #contacts{
        background-color: black;
        height: 100px;
        width: 100%;
        align-self: flex-end;
        display: flex;
        justify-content: space-around;
        align-items: center;
        button {
            padding: 20px;
            background-color: transparent;
            width: 200px;

            span{
                color: white;
                font-size: 20px;
            }
        }
        #social{
            display: flex;
            li {
                list-style-type: none;
                margin: 0 20px;
                a{
                    text-decoration: none;
                    h2{
                        color: blue;
                        font-size: 30px;
                    }
                }
            }
        }
    }
    

</style>