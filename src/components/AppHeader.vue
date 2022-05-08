<template>
  <header>
    <img src="../assets/img/dc-logo.png" alt="logo">
    <nav>
      <ul>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">Tv</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Collectibles</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">Fans</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Shop</a></li>
      </ul>
    </nav>
  </header>

</template>

<script>
export default {
  name: 'AppHeader',
 
}
</script>


<style scoped lang="scss">
@import "../style/generals.scss";
header {
    text-align: center;
    ul {
        list-style: none;
        margin: 2.5rem 1rem 4rem;
      
        li{
          display: inline-block;
          a {
            padding: 1rem;
            text-decoration: none;
          }
        } 
    }
}
nav{
  display: inline-block;
   vertical-align: 20px;
}
img{
  width: 3%;
}
</style>
