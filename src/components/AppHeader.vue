<script>
    export default{
        name: 'AppHeader'
    }
</script>

<template>
    <header class="container">
        <div>
            <img src="../assets/dc-logo.png" alt="">
        </div>
        <div>
            <ul>
                <li>CHARACTERS</li>
                <li class="selected">COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </div>

    </header>
</template>

<style lang="scss" scoped>
    header{
        display: flex;
        padding: 15px;
        justify-content: space-between;
        align-items: center;
    }
    img{
        width:80px;
    }
    ul{
        display: flex;
        li{
            list-style: none;
            margin: 15px;
            font-size: 0.9rem;
            font-weight: 600;
            cursor: pointer;
        }
    }
    .selected{
        color:#0282f9;
        border-bottom: 3px solid #0282f9;
    }
</style>