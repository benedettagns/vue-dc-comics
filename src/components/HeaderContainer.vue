<template>
    <header>
        <div class="logo-box">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>

        <ul>
            <li>characters</li>
            <li>comics</li>
            <li>movies</li>
            <li>tv</li>
            <li>games</li>
            <li>collectibles</li>
            <li>video</li>
            <li>fans</li>
            <li>news</li>
            <li>shop</li>
        </ul>    
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
header{
    height: 100px;
    width: 100%;
    display: flex;
    justify-content: space-around;
    
    .logo-box {
        margin-top: 15px ;

        img {
            width: 80px;
        }
    }
    
    ul {
        list-style: none;
        display: flex;
        margin-top: 40px;
        
        li {
            padding: 10px;
            text-transform: uppercase;
            cursor: pointer;

            &:hover {
                border-bottom: 3px blue solid;
            }
        }
    }
    
}

</style>