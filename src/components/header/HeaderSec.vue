<template>
  <div class="header">

    <SideBar />
    <MobileMenu />
  </div>
</template>

<script>
import SideBar from './SideBar.vue';
import MobileMenu from './MobileMenu.vue';
export default {
  name: 'HeaderSec',
  components: {
    SideBar,
    MobileMenu
  }

}
</script>

<style lang="scss" scoped>
</style>