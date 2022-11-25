<script>
import AppInformation from './another-comp/AppInformation.vue';
import socialBar from './another-comp/SocialBar.vue';

export default {
    name: 'AppFooter',
  data() {
    return {
      title: 'ciao'
    }
  },
  components:{
    AppInformation,
    socialBar
  }
}
</script>

<template>
  <footer>
    <section class="first-section-footer">
            <AppInformation/>
    </section>
    <section class="second-section-footer">
        <socialBar/>
    </section>
  </footer>
</template>

<style scoped>
.second-section-footer{
    background-color: var(--bg_footer);
}
</style>


