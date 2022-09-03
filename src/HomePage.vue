<template>
  <HeaderSec />
  <main class="page-wrapper-two">
    <BannerSec />
  </main>
</template>

<script>

import HeaderSec from './components/header/HeaderSec.vue';
import BannerSec from './pages/BannerSec.Vue'


export default {
  name: 'HomePage',
  components: {
    HeaderSec,
    BannerSec,
  }
}
</script>


