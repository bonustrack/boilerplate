<template>
  <nav class="nav-footer text-center p-4 mt-6">
    <ul>
      <li class="mx-3">shitcoin © {{new Date().getFullYear()}}</li>
      <li class="mx-3">Privacy policy</li>
    </ul>
  </nav>
</template>

<style scoped lang="less">
@import '../vars';

.nav-footer {
  background-color: @secondary-color;
  width: 100%;
  font-size: 16px;

  ul {
    li {
      display: inline-block;
    }
  }
}
</style>
