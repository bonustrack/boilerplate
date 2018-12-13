<template>
  <span>
    <div class="hero dark mb-6">
      <div class="app-container py-12 flex-auto anim-fade-in">
        <div class="columns">
          <div class="column col-lg-8 col-md-9 text-center text-md-left p-5">
            <h1 class="mb-4">The easiest way to create your own shitcoin</h1>
            <h4 class="mb-8">Your stunning shitcoin is just a few clicks away.</h4>
            <router-link to="/#start" class="btn-basic">
              Start now
            </router-link>
          </div>
          <div class="column col-lg-4 col-md-3 p-5 text-md-center">
            <div class="preview" style="width: 200px; height: 250px;"/>
          </div>
        </div>
      </div>
      <div class="hero-banner"/>
    </div>
    <div class="app-container py-6">
      <div class="columns">
        <div class="column col-7 p-5">
          <div class="preview"/>
        </div>
        <div class="column col-5 p-5">
          <h2 class="mb-4">Ut enim ad minim veniam</h2>
          <h4 class="mb-8">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</h4>
        </div>
      </div>
    </div>
    <div class="app-container py-6">
      <div class="columns">
        <div class="column col-5 p-5">
          <h2 class="mb-4">Quis nostrud exercitation</h2>
          <h4 class="mb-8">ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate</h4>
        </div>
        <div class="column col-7 p-5">
          <div class="preview"/>
        </div>
      </div>
    </div>
    <div class="app-container py-6">
      <div class="columns">
        <div class="column col-7 p-5">
          <div class="preview"/>
        </div>
        <div class="column col-5 p-5">
          <h2 class="mb-4">Velit esse cillum dolore eu</h2>
          <h4 class="mb-8">fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</h4>
        </div>
      </div>
    </div>
    <div class="dark mt-6 py-6">
      <div class="app-container text-center">
        <div class="columns">
          <div class="mx-auto col-8 p-5">
            <h2 class="mb-4">Ut enim ad minim veniam</h2>
            <h4 class="mb-8">ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate</h4>
            <router-link to="/#start" class="btn-basic">
              Start now
            </router-link>
          </div>
        </div>
      </div>
    </div>
  </span>
</template>

<style scoped lang="less">
@import '../vars';

.hero {
  min-height: 100%;
  display: flex;
  flex-direction: column;
  width: 100%;

  .hero-banner {
    width: 100%;
    height: 100px;
    background-color: @secondary-color;
  }
}
</style>
