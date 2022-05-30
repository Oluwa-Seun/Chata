import Bottomnav from '@/components/Navigation/Bottomnav.vue';

<template>
  <div class="app" v-if="!laptop">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
  </div>
  <div v-else class="laptop-message flex flex-column">
    <h2> sorry this can only be viewed on mobile devices</h2>
   </div>
</template>

<style lang="scss">
#app {
  overflow: hidden;
   background-color: black;
  min-height: 100vh;
  @media (min-width: 750px) {
    flex-direction: row !important;
  }
}
</style>

<script>

export default {
  data() {
    return {
      laptop: null,
    };
  },
  created() {
    this.checkScreen();
    window.addEventListener('resize', this.checkScreen);
  },
  methods: {
    checkScreen() {
      const windowWidth = window.innerWindo;
      if (windowWidth <= 350) {
        this.laptop = true;
        return;
      }
      this.laptop = false;
    },
  },
};
</script>
