<script>
import AppInformation from './another-comp/AppInformation.vue';

export default {
    name: 'AppFooter',
  data() {
    return {
      title: 'ciao'
    }
  },
  components:{
    AppInformation,
  }
}
</script>

<template>
    <section class="first-section-footer">
            <AppInformation/>
    </section>
    <section class="second-section-footer">

    </section>
</template>

<style scoped>

</style>


