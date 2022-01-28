<template>
    <div class="main">
        <div class="card-container">        
            <div v-for="(card, index) in cards" :key="index" class="box-card">
                <img :src="card.thumb" alt="">
                <p> {{card.series}} </p>
            </div>
        </div>

        <div class="button">LOAD MORE</div>
    </div>
</template>

<script>
export default {
    props: {
        cards: Array
    }  
}
</script>

<style lang="scss" scoped>

.main {
    background-color: rgb(37, 37, 37);
    height: 650px;

    .card-container {
        width: 1200px;
        margin: 0 auto;
        display: flex;
        flex-wrap: wrap;

        .box-card {
            width: calc(100% / 6);
            height: 200px;
            margin-top: 60px;
            padding: 10px;
            
            img {
                width: 100%;
                height: 100%;
            }

            p {
                text-transform: uppercase;
                padding-bottom: 10px;
                color: white;
                font-size: 14px;
            }
        }
    }  
    
    .button {
        width: 150px;
        height: 40px;
        background-color: blue;
        margin-top: 50px;
        margin-left: 600px;
        text-align: center;
        padding-top: 10px;
        color: white;
    }
}

</style>