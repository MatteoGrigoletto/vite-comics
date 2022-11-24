<script>
export default{
    name:'navShop',
    data(){
        return{
            list: '../../assets/img/buy-comics-digital-comics.png'
        }
    }
}
</script>
<template>
    <div>
        <ul>
            <li>
                <div class="img-box">
                    <img src="../../assets/img/buy-comics-digital-comics.png" alt="">
                </div>
                <div>
                    <a href="#">DIGITAL COMICS</a>
                </div>
            </li>
            <li>
                <div class="img-box">
                    <img src="../../assets/img/buy-comics-merchandise.png" alt="">
                </div>
                <div>
                    <a href="#">DC MERCHANDISE</a>
                </div>
            </li>
            <li>
                <div class="img-box">
                    <img src="../../assets/img/buy-comics-subscriptions.png" alt="">
                </div>
                <div>
                    <a href="#">SUBSRIPTION</a>
                </div>
            </li>
            <li>
                <div class="img-box">
                    <img src="../../assets/img/buy-comics-shop-locator.png" alt="">
                </div>
                <div>
                    <a href="#">COMIC SHOP LOCATOR</a>
                </div>
            </li>
            <li>
                <div class="img-box">
                    <img src="../../assets/img/buy-dc-power-visa.svg" alt="">
                </div>
                <div>
                    <a href="#">DC POWER VISA</a>
                </div>
            </li>
        </ul>
    </div>
  
</template>

<style scoped lang="scss">
ul{
    display: flex;
    justify-content: space-around;
    padding: 40px 20px 40px 20px;
    li{
        display: flex;
        align-items: center;
            .img-box{
                width: 70px;
                padding-right: 10px;
            }    
            a{
                text-decoration: none;
                color: var(--primary_color);
            }
        }
    }
</style>