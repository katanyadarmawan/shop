<template>
  <div class="home">
   <header-shop />
   <hero-shop />
   <item-shop />
   <insta-shop />
   <partner-shop />
   <footer-shop />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

import HeaderShop from '@/components/HeaderShop.vue';
import HeroShop from '@/components/HeroShop.vue';
import ItemShop from '@/components/ItemShop.vue';
import InstaShop from '@/components/InstaShop.vue';
import PartnerShop from '@/components/PartnerShop.vue';
import FooterShop from '@/components/FooterShop.vue';

export default {
  name: 'Home',
  components: {
    HeaderShop,
    HeroShop,
    ItemShop,
    InstaShop,
    PartnerShop,
    FooterShop
  }
}
</script>


