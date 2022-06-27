import Bottomnav from '@/components/Navigation/Bottomnav.vue';

<template>
  <div class="app laptop" :class="{mobile, Hero, hasHeader, showSidebar}">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
  </div>

</template>

<style lang="scss">
.mobile .laptop {
  background-color: #000;
}
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
      mobile: window.innerWidth <= 700,
    };
  },
  created() {
    window.addEventListener('resize', () => {
      this.mobile = window.innerWidth <= 700;
    });
  },
};
</script>
