<template>
    <div>

        
        <ul>
            <li v-for="(link, index) in links" :key="index">
                    <a  :href="link.url">
                 <!-- <img :src="'../assets/img/'+ links.img+ '.png'" :alt="link.text"> -->
                 <!-- <img src="../assets/img/buy-comics-digital-comics.png" alt=""> -->
                    
                        {{ link.text }}
                    </a>
                </li>
       
      </ul>
      
    </div>
</template>

<script>
export default {
    name: 'AppInfo',
    data(){
        return{
            links: [
                {
                    text: "Digita Comics",
                    url: "#",
                    img:"buy-comics-digital-comics",
                },
                {
                    text: "DC merchandise",
                    url: "#",
                    img:"buy-comics-merchandise",
                },
                {
                    text: "Subscription",
                    url: "#",
                    img:"buy-comics-subscriptions",
                },
                {
                    text: "Comics shop locator",
                    url: "#",
                    img:"buy-comics-shop-locator",
                },
                {
                    text: "DC power visa",
                    url: "#",
                    img:"buy-comics-subscriptions",
                },
                
            ],

                    
        }
    }
}

</script>

<style scoped lang="scss">
@import "../style/generals.scss";
div{
    text-align: center;
    background-color: #0282F9;
}
    ul {
        list-style: none;
        
      
        li{
          display: inline-block;
          a {
            padding: 1rem;
            text-decoration: none;
            color: white;
          }
        } 
    }
</style>