<script>
 export default{
    name: ' navBar',
    data(){
        return{
            navItems:[
                'CHARACTERS ',
                'COMICS',
                'MOVIES',
                'TV',
                'GAMES',
                'COLLECTIBLES',
                'VIDEOS',
                'FANS',
                'NEWS',
                'SHOP',
            ],
        }
    }
 }
</script>
<template>
    <div class="nav-bar">
        <ul>
            <li v-for="item in navItems"><a href="#">{{item}}</a></li>
        </ul>
    </div>
</template>
<style lang="scss" scoped>
.nav-bar{

    ul {
        display: flex;
        list-style: none;

        a {
            text-decoration: none;
            padding: 0px 10px;
            color: inherit;
            font-weight: bold;
        }
    }
    
    }

</style>