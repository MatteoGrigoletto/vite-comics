<script>
export default{
    name:'AppInformation',
    data(){
        return{
            dcComics:[
                'characters',
                'comics',
                'Movies',
                'TV',
                'Games',
                'Videos',
                'News',
            ],
            shop:[
                'Shop DC',
                'Shop DC Collectibles',
            ],
            dc:[
                'Term of use',
                'Privacy policy (new)',
                'Ad Choices',
                'Advertising',
                'Jobs',
                'Subscription',
                'Talent Workshops',
                'CPSC Certifactes',
                'Rating',
                'Shop help',
                'Contact Us',
            ],
            sites:[
                'DC',
                'MAD',
                'DC Kids',
                'DC Universe',
                'DC Power Visa',
            ]
        }
    }
}
</script>

<template>
    <div class="bg-heros">
        <div class="information-link container">
            <div >
                <h4>DC COMICS</h4>
                <ul>
                    <li v-for="comic in dcComics" ><a href="#">{{comic}}</a></li>
                </ul>
                <h4>SHOP</h4>
                <ul>
                    <li v-for="item in shop" ><a href="#">{{item}}</a></li>
                </ul>
            </div>
            <div>
                <h4>DC</h4>
                <ul>
                    <li v-for="info in dc"><a href="#">{{info}}</a></li>
                </ul>
            </div>
            <div>
                <h4>SITES</h4>
                <ul>
                    <li v-for="site in sites"><a href="#">{{site}}</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.bg-heros{
    background-image: url('../../assets/img/footer-bg.jpg');
}
.information-link{
    padding: 40px 0px;
    display: flex;
        div{
            padding-right: 30px;
    h4{
        color: var(--primary_color);
        padding: 5px 0px;
    }
    ul{
        list-style: none;
        li{
            padding: 5px 0px;
            a{
                text-decoration: none;
                color: var(--color_information_link);
            }
        }
    }
}
}
</style>