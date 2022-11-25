<script>
    export default{
        name: 'AppBanner',
        data(){
            return{}
        },
        props:{
            text: String,
        }
    }
</script>
<template>

    <button class="btn">
         {{text}}
    </button>

</template>

<style lang="scss" scoped>

button{
    background-color: var(--bg_second_section);
    color: var(--primary_color);
    height: 30px;
    font-weight:bold ;
    padding: 5px 20px;
}
</style>