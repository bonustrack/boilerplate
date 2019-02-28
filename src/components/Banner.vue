<template>
  <div class="banner b-color-primary mb-6">
    <div class="container py-12 flex-auto anim-fade-in">
      <div class="columns">
        <div class="column col-lg-8 col-md-9 text-center text-md-left p-5">
          <h1 class="title mb-4">
            Play Fun Games and earn real money
          </h1>
          <h4 class="subtitle text-white mb-8">
            Make Steem first on crypto online gaming
          </h4>
          <router-link to="/center" class="btn-basic">
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

.b-banner-inside {
  background: url('./../assets/img/games-center-banner-xl.jpg') no-repeat;
}
.banner {
  position: relative;
  z-index: 0;
  height: 100vh;

  .title {
    // color: @banner-title-color;
    font-size: @banner-title-size;
    font-family: 'Circular-Pro-Bold';
    line-height: 1;
  }
  .subtitle {
    // color: @banner-subtitle-color;
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

</style>
