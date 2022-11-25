<script>
export default{
    name:'socialBar',
    data(){
        return{}
    }
}
</script>
<template>
<div class="container">
    <div >
        <button class="btn-footer"> SIGN-UP NOW!! </button>
    </div>
    <div>
        <ul>
            <li>FOLLOW US</li>
            <li><a href="#"><i class="fa-brands fa-facebook"></i></a></li>
            <li><a href="#"><i class="fa-brands fa-twitter"></i></a></li>
            <li><a href="#"><i class="fa-brands fa-youtube"></i></a></li>
            <li><a href="#"><i class="fa-brands fa-sass"></i></a></li>
            <li><a href="#"><i class="fa-solid fa-spinner"></i></a></li>
        </ul>
    </div>
</div>
</template>
<style lang="scss" scoped>
.container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 31px 0px;

    ul{
        display: flex;
        list-style: none;
        
        li{
            padding: 0px 30px;
            color: var(--bg_second_section);
            font-weight: bold;
            font-size: 20px;
            
            a{
                text-decoration: none;
                color: var(--primary_color);
            }
        }
    }
}
.btn-footer{
    border: 2px solid var(--bg_second_section);
    background-color: transparent;
    padding: 15px;
    color: var(--primary_color);
    font-weight: bold;
}

</style>