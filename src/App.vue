<script src="../build/webpack.dev.conf.js"></script>
<template>
  <div id="app">
    <Header></Header>
    <div class="tab">i am tab</div>
    <div class="content">i am content</div>
  </div>
</template>

<script>
import header from './components/header/header';
export default {
  comments:{
    'Header': header
  }
};
</script>

<style>
#app {

}
</style>
