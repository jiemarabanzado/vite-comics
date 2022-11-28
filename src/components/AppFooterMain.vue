<script>
    export default{

    }
</script>
<template>
    <footer>
        <div class="container">
            <div class="foot-nav row">
                <div class="first-column">
                    <div class="dc-comics">
                        <h3>DC COMICS</h3>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>Tv</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                    </div>
                    <div class="shop">
                        <h3>SHOP</h3>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC collectibles</li>
                        </ul>
                    </div>
                </div>
                <div class="second-column">
                    <h3>DC</h3>
                    <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>Tv</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                            <li>Tv</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>

                </div>
                <div class="third-column">
                    <h3>SITES</h3>
                    <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>Tv</li>
                            <li>Games</li>
                            
                        </ul>
                </div>
                
            </div>
            <img src="../assets/dc-logo-bg.png" alt="">
        </div>
    </footer>
</template>
<style lang="scss" scoped>
    footer{
        
        background-image: url(../assets/footer-bg.jpg);
    }
    .container{
        padding: 30px 15px;
        position: relative;
        overflow: hidden;
    }
    .dc-comics , .shop , .second-column ,.third-column{
        margin-right: 25px;
        font-size: 0.9rem;
        color: white;
        margin-bottom: 20px;
        h3{
            margin-bottom: 10px;
        }
        ul li{
            list-style: none;
            margin-bottom: 5px;
            font-size: 0.8rem;
            color: #959595;
        }
    }
    img{
        position: absolute;
        width: 500px;
        bottom: -80px;
        right: 0;
    }
</style>