<template>
  <footer role="footer">
    <nav class="nav-footer text-center p-4">
      <ul>
        <li class="mx-3">Steem Games © {{new Date().getFullYear()}}</li>
        <li class="mx-3">Privacy policy</li>
      </ul>
    </nav>
  </footer>
</template>

<style scoped lang="less">
@import '../assets/less/vars';

.nav-footer {
  background-color: @bg-color;
  width: 100%;
  font-size: 16px;

  ul {
    li {
      display: inline-block;
    }
  }
}
</style>
