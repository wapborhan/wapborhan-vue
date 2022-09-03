<template>
  <div id="home" class="slider-style-5  pb--110 align-items-center with-particles">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="banner-inner">
            <div class="thumbnail gradient-border havatar gradient-animationz">
              <img id="border" class="gradient-border image gardnt" src="https://wapborhan.com/images/banner.jpg"
                alt="" />
              <span class="gradient-borders"></span>
            </div>
            <h1>Borhan Uddin</h1>

            <span class="cd-headline clip is-full-width">
              <div class="info">
                <span>
                  Founder &amp; CEO
                  <span class="textlight">SR Dream Lab</span>
                </span>
              </div>
            </span>

            <div class="button-area">
              <BannerSocial />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import BannerSocial from "./BannerSocial.vue"
export default {
  name: 'BannerSec',
  components: {
    BannerSocial
  }

}
</script>

<style>
.textlight {
  color: black;
}
</style>