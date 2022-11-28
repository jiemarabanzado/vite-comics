<script>
</script>
<template>
    <div class="foot">
        <div class="container row">
            <div>
                <button>SIGN-UP NOW</button>
            </div>
            <div class="right-footer row">
                <h4>FOLLOW US</h4>
                <div><img src="../assets/footer-facebook.png" alt=""></div>
                <div><img src="../assets/footer-periscope.png" alt=""></div>
                <div><img src="../assets/footer-pinterest.png" alt=""></div>
                <div><img src="../assets/footer-twitter.png" alt=""></div>
                <div><img src="../assets/footer-youtube.png" alt=""></div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .foot{
        background-color: #303030;
        padding: 30px 0px;
    }
    .container{
        justify-content: space-between;
        align-items: center;
    }
    .right-footer{
        align-items: center;
        h4{
            margin-right: 20px;
            color: var(--primary-color)
        }
        img{
            margin-right: 10px;
        }
    }
    button{
        padding: 10px;
        color: white;
        background-color: transparent;
        border: 2px solid var(--primary-color);
    }
</style>