<template>
  <section class="game-list py-10">
    <h2 class="container-xl mb-3 px-3 text-white f2">Games</h2>
    <div class="container-xl d-flex">
      <div class="col mx-3 anim-fade-in hover-grow">
        <div class="d-flex flex-column">
          <div class="col">
            <div class="preview preview-steemmonsters"/>
          </div>
          <div class="col p-3 pb-10 game-list--body border-top-0">
            <h3 class="mb-2 text-white text-uppercase">
              Steem Monsters
            </h3>
            <p class="mb-2 text-white">
              A decentralized, digital collectible trading card game built on the Steem blockchain!
           </p>
          </div>
        </div>
      </div>
      <div class="col mx-3 anim-fade-in hover-grow">
        <div class="d-flex flex-column">
          <div class="col">
            <div class="preview preview-drugwars"/>
          </div>
          <div class="col p-3 pb-10 game-list--body border-top-0">
            <h3 class="mb-2 text-white text-uppercase">
              Drugwars
            </h3>
            <p class="mb-2 text-white">
              Build your own empire, Fight with your opponents, Get rewarded with cryptocurrency
           </p>
          </div>
        </div>
      </div>
      <div class="col mx-3 anim-fade-in hover-grow">
        <div class="d-flex flex-column">
          <div class="col">
            <div class="preview preview-magicdice"/>
          </div>
          <div class="col p-3 pb-10 game-list--body border-top-0">
            <h3 class="mb-2 text-white text-uppercase">
              Magic Dice
            </h3>
            <p class="mb-2 text-white">
              A decentralized, digital collectible trading card game built on the Steem blockchain!
           </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="less">
@import '../assets/less/vars';

.game-list {
  background-image: url('./../assets/img/game-list-background.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  p {
    color: rgba(255,255,255,.6) !important;
  }
  &--body {
    background-color: rgba(0,174,255,.1);
    border: 1px solid rgba(255, 255, 255, .2);
    background-clip: padding-box;
  }

  .preview {
    display: block;
    width: 100%;
    height: 190px;
    background-position: center top;
    background-size: 100% auto;
    &-steemmonsters {
      background-image: url('./../assets/img/steemmonsters.jpg');
    }
    &-drugwars {
      background-image: url('./../assets/img/drugwars.jpg');
    }
    &-magicdice {
      background-image: url('./../assets/img/magic-dice.jpg');
    }
  }

}
</style>
