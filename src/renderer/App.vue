<template>
  <div id="app">
    <div class="titlebar"></div>
    <router-view></router-view>
  </div>
</template>

<script>
  export default {
    name: 'work_manager'
  }
</script>

<style>
  body {
    overflow: hidden;
  }

  .titlebar {
    background: radial-gradient( ellipse at top left, rgba(255, 255, 255, 1) 40%, rgba(229, 229, 229, .9) 100% );
    width: 100%;
    height: 22px;
    -webkit-user-select: none;
    -webkit-app-region: drag;
  }

  .titlebar > button {
    -webkit-app-region: no-drag;
  }
</style>
