<template>
  <div>
    <s-button icon="settings" :loading="loading" @click="loading=!loading">默认按1111111111钮</s-button>
  </div>
</template>
<script>
import Button from "./button/button";
export default {
  data() {
    return {
      loading: true
    };
  },
  components: {
    "s-button": Button
  }
};
</script>

<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>