<template>
  <div id="root">
    <p>{{ originalPirce }}</p>
    <p>{{ doublePrice }}</p>
    <p>{{ triplePrice }}</p>
  </div>
  
</template>

<script>
import { mapGetters } from 'vuex';

export default {
  computed: {
    ...mapGetters(["originalPirce", "doublePrice", "triplePrice"])

    // originalPirce() {
    //   return this.$store.getters.originalPirce;
    // },
    // doublePrice() {
    //   return this.$store.getters.doublePrice;
    // },
    // triplePrice() {
    //   return this.$store.getters.triplePrice;
    // }
  }
}
</script>

<style>

</style>