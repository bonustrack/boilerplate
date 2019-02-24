<template>
  <span>
    <div class="list app-container">
      <div class="list-row lottery py-6">
        <div class="columns">
          <div class="column col-7 p-5">
            <div class="preview"/>
          </div>
          <div class="column col-5 p-5">
            <h2 class="mb-4">
              Daily lottery
            </h2>
            <h4 class="mb-8">
              Win every day really big price $100000 minimum
           </h4>
          </div>
        </div>
      </div>
      <div class="list-row jackpot py-6">
        <div class="columns">
          <div class="column col-5 p-5">
            <h2 class="mb-4">
              Free Jackpot
            </h2>
            <h4 class="mb-8">
              Play for FREE and win the daily jackpot $10
            </h4>
          </div>
          <div class="column col-7 p-5">
            <div class="preview"/>
          </div>
        </div>
      </div>
      <div class="list-row number py-6">
        <div class="columns">
          <div class="column col-7 p-5">
            <div class="preview"/>
          </div>
          <div class="column col-5 p-5">
            <h2 class="mb-4">Lucky number</h2>
            <h4 class="mb-8">
              Everyday during the lottery you can win money with only one lucky number
            </h4>
          </div>
        </div>
      </div>
    </div>
  </span>
</template>

<style scoped lang="less">
@import '../assets/less/vars';

.list {
  &-row {
    .preview {
      display: block;
      width: 520px;
      height: 330px;
    }
    &.lottery {
      .preview {
        background: url('./../assets/img/lottery.jpg') no-repeat;
      }
    }
    &.jackpot {
      .preview {
        background: url('./../assets/img/jackpot.jpg') no-repeat;
      }
    }
    &.number {
      .preview {
        background: url('./../assets/img/luckynumber.jpg') no-repeat;
      }
    }
  }

}
</style>
