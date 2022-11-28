<script>
    export default{

    }
</script>
<template>
    <div class="foot-header">
        <div class="container row">
            <div class="buy row">
                <div>
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                </div>
                <div>
                    DIGITAL  COMICS
                </div>
            </div>
            <div class="buy row">
                <div>
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                </div>
                <div>
                    DC MERCHANDISE
                </div>
            </div>
            <div class="buy row">
                <div>
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                </div>
                <div>
                    SUBSCRIPTIONS
                </div>
            </div>
            <div class="buy row">
                <div>
                    <img src="../assets/buy-comics-shop-locator.png" alt="">
                </div>
                <div>
                    SHOP LOCATOR
                </div>
            </div>
            <div class="buy row">
                <div>
                    <img src="../assets/buy-dc-power-visa.svg" alt="">
                </div>
                <div>
                    DC POWER VISA
                </div>
            </div>
        </div>
    </div>
    
</template>
<style lang="scss" scoped>
    .foot-header{
        background-color: var(--primary-color);
    }
    .container{
        padding: 40px;
        justify-content: space-between;
    }
    img{
        width: 45px;
    }
    .buy{
        width: calc(100%/5 - 20px);
        align-items: center;
        div:nth-child(2){
            color: white;
        }
        div:nth-child(1){
            margin-right: 10px;
        }
    }
</style>