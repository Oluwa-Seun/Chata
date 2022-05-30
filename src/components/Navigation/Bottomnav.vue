import Bottomnav from '@/components/Navigation/Bottomnav.vue';

<template>
<div id="navbar">
  <nav class="navbar1 navbar-expand navbar-dark bg-white text-white fixed-bottom">
<ul class="navbar-nav nav-justified w-100">
  <li class="nav-item">
    <a href="" class="nav-link"><Home /></a>
  </li>
  <li class="nav-item">
    <a href="" class="nav-link"><Wallet /></a>
  </li>
  <li class="nav-item">
    <a href="" class="nav-link"><Pickup/></a>
  </li>
  <li class="nav-item">
    <a href="#" class="nav-link"><Account/></a>
  </li>
</ul>
  </nav>
  </div>
</template>

<script>
import Home from '../Icon/Home.vue';
import Pickup from '../Icon/Pickup.vue';
import Wallet from '../Icon/Wallet.vue';
import Account from '../Icon/Account.vue';

export default {
  name: 'Bottomnav',
  components: {
    Home,
    Pickup,
    Wallet,
    Account,
  },
};
</script>
<style lang="scss">
@import "../../assets/scss/style.scss";
.navbar1{
height: 10%;
align-items: center;
}
</style>
