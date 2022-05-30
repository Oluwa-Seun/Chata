<template>
  <div class="home">
    <Navbar />
    <Hero />
    <Trust />
    <Achievements />
    <Connections />
    <Bottomnav />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navigation/Navbar.vue';
import Bottomnav from '@/components/Navigation/Bottomnav.vue';
import Hero from '@/components/Sections/Hero.vue';
import Achievements from '@/components/Sections/Achievements.vue';
import Connections from '@/components/Sections/Connections.vue';

export default {
  name: 'Home',
  components: {
    Navbar,
    Hero,
    Achievements,
    Connections,
    Bottomnav,
  },
};
</script>
