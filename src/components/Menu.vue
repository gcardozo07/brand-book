<template>
      <div class="menu">
          <ul>
              <li><router-link to="/">Brand Guidelines</router-link></li>
              <li><span>LOGO & LOGO LOCKUPS</span></li>
              <li><router-link to="/logo">Avaya Logo</router-link></li>
              <li><router-link to="/lockups">Logo Lockups</router-link></li>
              <li><router-link to="/products">Product Lockups</router-link></li>
              <li><span>COLOR</span></li>
              <li><router-link to="/values">Color Values</router-link></li>
              <li><router-link to="/Assignments">Assignments</router-link></li>
              <li><router-link to="/Colorphoto">Color in Photography</router-link></li>
              <li><span>PATTERNS</span></li>
              <li><router-link to="/Brandpatterns">Brand Patterns</router-link></li>
              <li><router-link to="/Productpatterns">Product Patterns</router-link></li>
          </ul>
      </div>
</template>

<script>
export default {
    components:{
        name: 'Menu'
    }
}
</script>

<style lang="scss">
$color: red;
$noto: "Noto Sans JP";

   .menu {
    width: 350px;
    min-height: 100vh;
    background: #004E6C;
    padding: 3rem;
    box-sizing: border-box;
    position: relative;
    background-image: url('../img/patt.png');
    background-size: contain;
    background-repeat: no-repeat;
    background-position: bottom;
    box-shadow: 2px 4px 10px 8px rgba(0, 0, 0, 0.1);
    @media screen and (max-width: 991px) {
                    width: 100%;
                    min-height: 100px;
                    background-position: right;
                    padding: 2rem;
                }
    ul{
        padding: 0;
        margin: 0;
        @media screen and (max-width: 991px) {
                    display: flex;
                    flex-wrap: wrap;
                }
        li{
            list-style: none;
            padding-bottom: 1rem;
            font-size: 1rem;
            font-family: $noto;
            color: #fff;
            text-align: left;
            @media screen and (max-width: 991px) {
                   margin: 0.2rem;
                }
            span{
                color: #45AF9A;
                font-weight: 400;
            }
        }
    }
    h1{
        color: #fff;
    }
} 

a.router-link-exact-active {
  color: #ffffff;
  font-weight: 700;
  text-decoration: none;
}

</style>