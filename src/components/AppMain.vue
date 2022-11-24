<script>
import navShop from './another-comp/NavShop.vue';

export default {
    name: 'AppMain',
  data() {
    return {
      
    }
  },
  components:{
    navShop,
  }
}
</script>

<template>
    <section class="first-section-main">
         <div class="container">
            <p> -- Content goes here -- </p>
        </div>
    </section>
    <section class="second-section-main">
        <div class="container">
            <navShop/>
        </div>
    </section>

</template>

<style lang="scss" scoped>
.first-section-main{
  background-color: var(--secondary_color);
    p{
        padding: 30px;
        color: var(--primary_color);
        font-size: 40px;
    }
}
.second-section-main{
  background-color: var(--bg_second_section);
}
</style>


