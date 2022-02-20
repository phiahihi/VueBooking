<template>
  <div id="app">

    <Main v-if="!mobileView" />
    <Mobileview v-else />
  </div>
</template>

<script>
import Main from "../src/components/Main.vue";
import Mobileview from "../src/components/Mobileview.vue";

export default {
  data: () => {
    return {
      mobileView: true,
    }
  },
  components: {
    Main,
    Mobileview,
  },
  methods: {
    handleView() {
      this.mobileView = window.innerWidth <= 990;
    }
  },
  created() {
    this.handleView();
    window.addEventListener('resize', this.handleView);
  }
}
</script>

<style>

li {
  list-style: none;
  cursor: pointer;
}
ul {
  display: flex;
  padding: 0;
}
</style>
