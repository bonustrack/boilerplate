<template>
  <header role="header">
    <nav class="nav-primary p-4">
      <router-link to="/">
        <span class="octicon octicon-primitive-dot v-align-middle"></span>
        <span class="site-name">Steem Games</span>
      </router-link>
    </nav>
  </header>
</template>

<style scoped lang="less">
@import '../assets/less/vars';

.nav-primary {
  position: absolute;
  top: 0;
  width: 100%;

  .site-name {
    color: @header-site-name-color;
    font-size: @header-site-name-size;
  }
}
</style>
