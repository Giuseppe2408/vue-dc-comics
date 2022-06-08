<template>

    <footer>
      <div>
        <ul>

          <li>
            <h1>DC COMICS</h1>
          </li>
          <li>
            <a href="">Characters</a>
          </li>
          <li>
            <a href="">Characters</a>
          </li>
          <li>
            <a href="">Characters</a>
          </li>
          <li>
            <a href="">Characters</a>
          </li>
          <li>
            <a href="">Characters</a>
          </li>
          <li>
            <a href="">Characters</a>
          </li>
          <li>
            <a href="">Characters</a>
          </li>
          <li>
            <h1>SHOP</h1>
          </li>
          <li>
            <a href="">Characters</a>
          </li>
          <li>
            <a href="">Characters</a>
          </li>
          <li>
            <a href="">Characters</a>
          </li>
        </ul>
        <ul>
          <li>
            <h1>DC</h1>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
          <li>
            <a href="">Terms of use</a>
          </li>
        </ul>
        <ul>
          <li>
            <h1>SITES</h1>
          </li>
          <li>
            <a href="">dc</a>
          </li>
          <li>
            <a href="">dc</a>
          </li>
          <li>
            <a href="">dc</a>
          </li>
          <li>
            <a href="">dc</a>
          </li>
          <li>
            <a href="">dc</a>
          </li>
          <li>
            <a href="">dc</a>
          </li>
          <li>
            <a href="">dc</a>
          </li>
          <li>
            <a href="">dc</a>
          </li>

        </ul>
      </div> 

      <div>
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
        
    </footer>
      
</template>

<script>
export default {
  name: 'DcFooter',
  
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    footer {
      background-image: url(../assets/img/footer-bg.jpg);
      background-size: contain;
      height: 600px;
      display: flex;
      justify-content: space-around;
      align-items: center;
      div {
        display: flex;
        ul{
        margin-right: 50px;
        li{
          list-style-type: none;

          h1{
            color: white;
          }
          a{
            text-decoration: none;
            color: grey;
          }
        }
      }
      }
      
    }
</style>