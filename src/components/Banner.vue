<template>
  <div class="banner dark mb-6">
    <div class="app-container py-12 flex-auto anim-fade-in">
      <div class="columns">
        <div class="column col-lg-8 col-md-9 text-center text-md-left p-5">
          <h1 class="title mb-4">
            Creating Winners Every Day
          </h1>
          <h4 class="subtitle mb-8">
            Play Fun Games and earn real money!
          </h4>
          <router-link to="/#start" class="btn-basic">
            Play now
          </router-link>
        </div>
        <div class="column banner-demo col-lg-4 col-md-3 p-5 text-md-center">
          <div class="preview"/>
        </div>
      </div>
    </div>
    <div class="hero-banner d-none"/>
  </div>
</template>

<style scoped lang="less">
@import '../assets/less/vars';

.banner {
  .title {
    color: @banner-title-color;
    font-size: @banner-title-size;
    font-family: 'Circular-Pro-Bold';
  }
  .subtitle {
    color: @banner-subtitle-color;
    font-size: @banner-subtitle-size;
  }
  .preview {
    background: url('./../assets/img/lottery.gif') no-repeat;
    display: inline-block;
    background-color: @primary-color;
    height: 450px;
    width: 310px;
    border-radius: 50px;
  }
}

.dark {
  color: @heading-dark-color;
  background-color: @bg-dark-color;
  // background-image: url('./assets/img/bg-banner.jpg');
  background-color: #2490EF;
  background-image: linear-gradient(264deg, #f8b314, #fff401 54%, #fee004);
  background-position: top center;
  background-attachment: fixed;
}


</style>
