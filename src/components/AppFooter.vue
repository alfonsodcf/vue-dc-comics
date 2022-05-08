<template>
  <footer>
  <div class="img">
    <div class="line">
      
      <div>
        <h4>Dc comics</h4>
        <nav>
          <ul>
            <li><a href="#">Il Pastificio</a></li>
            <li><a href="#">Grano</a></li>
            <li><a href="#">Filiera</a></li>
            <li><a href="#">100 anni di pasta</a></li>
            <li><a href="#">Sartoria della pasta</a></li>
          </ul>
        </nav>
      </div>

      <div>
        <h4>Shop</h4>
        <nav>
          <ul>
            <li><a href="#">Le classiche</a></li>
            <li><a href="#">Le Integrali</a></li>
            <li><a href="#">Le Speciali</a></li>
            <li><a href="#">Le Biologiche</a></li>
            <li><a href="#">Le Gluten-free</a></li>
          </ul>
        </nav>
      </div>
    </div>
    
    
      
      <div class="line">
        <h4>Dc</h4>
        <nav>
          <ul>
            <li><a href="#">Le classiche</a></li>
            <li><a href="#">Le Integrali</a></li>
            <li><a href="#">Le Speciali</a></li>
            <li><a href="#">Le Biologiche</a></li>
            <li><a href="#">Le Gluten-free</a></li>
          </ul>
        </nav>
      </div>
      <div class="line">
        <h4>Sites</h4>
        <nav>
          <ul>
            <li><a href="#">Le classiche</a></li>
            <li><a href="#">Le Integrali</a></li>
            <li><a href="#">Le Speciali</a></li>
            <li><a href="#">Le Biologiche</a></li>
            <li><a href="#">Le Gluten-free</a></li>
          </ul>
        </nav>
      </div>
      <img src="../assets/img/dc-logo-bg.png" alt="dc-logo-bg">
  </div>
    <div class="footerfoter">
      <div class="linea">
        <a href="#">Sign-up now!</a>
      </div>
      <div class="linea">
        <p>Follow us</p>
      </div>
      <div class="linea">
        <img src="../assets/img/footer-facebook.png" alt="facebook">
        <img src="../assets/img/footer-twitter.png" alt="twitter">
        <img src="../assets/img/footer-youtube.png" alt="youtube">
        <img src="../assets/img/footer-pinterest.png" alt="pinterest">
        <img src="../assets/img/footer-periscope.png" alt="periscope">
      </div>
      
    </div>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter.vue',
 
}
</script>


<style scoped lang="scss">

  .img{
    .line{
      display: inline-block;
      h4{
        color: white;
        font-size: 1.25em;
        font-weight: 600;
        margin-bottom: 1rem;
      }
      ul{
        list-style: none;
        
      }
      
    }
    background-image: url(../assets/img/footer-bg.jpg);
    img{
      width: 350px;
    }

  }
  .footerfoter{
    background-color: #303030;
    a{
      padding: 5px;
      border: 1px solid #0184F7;
    }
    p{
      color: #0184F7;
    }
  }
  
a{
  color: white;
  text-decoration: none;
  &:hover{
    color: blue
  }
}
.linea{
  display: inline-block;
}

</style>
