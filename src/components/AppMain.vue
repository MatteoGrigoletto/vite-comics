<script lang="js">
import navShop from './another-comp/NavShop.vue';
import AppList from './another-comp/AppList.vue';
import AppBanner from './another-comp/AppBanner.vue';

export default {
    name: 'AppMain',
  data() {
    return {
      
    }
  },
  components:{
    navShop,
    AppList,
    AppBanner,
  }
}
</script>

<template>
  <main>
    <section class="first-section-main">
         <div class="container"></div>
    </section>
    <section class="second-section-main">
      <div class="container">
        <AppBanner class="current-film" text=" CURRENT SERIES"/>
        <AppList/>
        <AppBanner class="load-more" text="LOAD MORE"/>
      </div>
    </section>
    <section class="third-section-main">
        <div class="container">
            <navShop/>
        </div>
    </section>
  </main>
</template>

<style lang="scss" scoped>

.first-section-main{
  background-image: url('../assets/img/jumbotron.jpg');
  background-size: cover;
  height: 400px;
}
.second-section-main{
  background-color: var(--secondary_color);
  text-align: center;
  position: relative;
  
  .current-film{
    position: absolute;
    left: 20%;
    top: -10px;
    padding:  5px 30px;
  }
  .load-more{
    margin-bottom: 10px;
  }
}
.third-section-main{
  background-color: var(--bg_second_section);
}
</style>


