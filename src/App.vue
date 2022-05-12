<template>
  <div id="app">
    <HelloTitle class="titolo" />
    <JumbotronImage />
  </div>
</template>

<script>

import HelloTitle from "./components/HelloTitle.vue";
import JumbotronImage from "./components/JumbotronImage.vue";

export default {
  name: 'App',
  components: {
    HelloTitle,
    JumbotronImage,
}
}
</script>

<style lang="scss">
 
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>
