<template>
    <div>
        <div class="navbar">
            
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <span>digital comics</span>
        
            <img src="../assets/img/buy-comics-merchandise.png" alt="">
            <span>dc merchandise</span>
        
            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            <span>subscriptions</span>
        
            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            <span>comic shop locator</span>
        
            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
            <span>dc power visa</span>
        
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.navbar {
    height: 100px;
    background-color: blue;
    display: flex;
    align-items: center;
    justify-content: center;
    
    img {
        width: 40px;
    }

    span {
        text-transform: uppercase;
        color: white;
        font-size: 12px ;
        margin-right: 70px;
        padding-left: 10px ;
    }
    
}
</style>