<template>
  <div id="app">
    <icon-svg class="re-icon" icon-class="dashboard" />
    <icon-svg class="re-icon" icon-class="404" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import IconSvg from './components/SvgIcon.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    IconSvg
  }
}
</script>

<style>
.icon {
  width: 1em;
  height: 1em;
  vertical-align: -0.15em;
  fill: currentColor;
  overflow: hidden;
}
.re-icon {
  width: 100px;
  height: 100px;
  cursor: pointer;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  max-width: 560px;
  min-height: 395px;
  border: 1px solid #eee;
  margin: 60px auto 0;
  box-shadow: 0 0 8px 0 rgba(232, 237, 250, 0.6),
    0 2px 4px 0 rgba(232, 237, 250, 0.5);
  border: 1px solid #ebebeb;
  border-radius: 3px;
  transition: 0.2s;
  padding: 1em;
}
</style>
