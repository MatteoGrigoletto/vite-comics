<script lang="js">
import navBar from './another-comp/nav.vue';
import logo from './another-comp/logo.vue';
export default {
  name: 'AppHeader',
  components:{
    navBar,
    logo,
  },
  data() {
    return {
      title: 'Il titolo della pagina'
    }
  }
}
</script>

<template>
  <header>
    <section class="first-section-header">
      <div class="container">
        <logo/>
        <navBar/>
      </div>
    </section>
  </header>
</template>

<style lang="scss" scoped>

header{
padding: 20px 0px;

    .first-section-header{
        background-color: var(--primary_color);
          .container{
          width: 1300px;
          margin: auto;
          display: flex;
          justify-content: space-between;
          align-items: center;
        }
    }
}
</style>


