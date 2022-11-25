<script lang="js">
import navShop from './another-comp/NavShop.vue';
import AppList from './another-comp/AppList.vue';

export default {
    name: 'AppMain',
  data() {
    return {
      
    }
  },
  components:{
    navShop,
    AppList,
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
        <AppList/>
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
}
.third-section-main{
  background-color: var(--bg_second_section);
}
</style>


