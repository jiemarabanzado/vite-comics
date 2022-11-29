<script>
    
</script>
<template>
    <main>
        <div class="jumbotron"><img  src="../assets/jumbotron.jpg" alt=""></div>
        <div class="container row">
            content goes here
        </div>

    </main>
</template>

<style lang="scss" scoped>
    main{
        
        background-color: #1c1c1c;
        min-height: 100px;
        div{
            color:white
        }
    }
    .container{
        padding: 15px;
    }
    .jumbotron{
        height: 350px;
        width: 100%;
        img{
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: top;
        }
    }
</style>