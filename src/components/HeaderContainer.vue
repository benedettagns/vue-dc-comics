<template>
    <header>
        <div class="logo-box">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>

        <ul>
            <li v-for="(element, index) in nav" :key="index">
                <a :href="element.url"> 
                    {{element.title}}
                </a>
            </li>
        </ul>    
    </header>
</template>

<script>
export default {

    data() {
        return {
            nav: [
                {
                title: 'characters',
                url: '/character',
                },
                {
                title: 'comics',
                url: '/comic',
                },
                {
                title: 'movies',
                url: '/movie',
                },
                {
                title: 'tv',
                url: '/television',
                },
                {
                title: 'games',
                url: '/game',
                },
                {
                title: 'collectibles',
                url: '/collectible',
                },
                {
                title: 'video',
                url: '/videos',
                },
                {
                title: 'fans',
                url: '/fan',
                },

                {
                title: 'news',
                url: '/new',
                },

                {
                title: 'shop',
                url: '/shops',
                },
            ],
        }
    }
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

            a {
                text-decoration: none;
                color: black;
            }
        }
    }
    
}

</style>