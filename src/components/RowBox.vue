<template>
    <div class="main">
        <div v-for="(card, index) in cards" :key="index" class="card-container">
            <div class="card-box">
                <img :src="card.thumb" alt="">
                <p>{{card.series}}</p>
            </div>
        </div>
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

    .card-container {
        width: 1200px;
        margin: 0 auto;

    }    
}

</style>