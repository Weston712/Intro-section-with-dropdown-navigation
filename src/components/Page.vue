<script>
import HeaderVue from "./Header.vue";

export default {
  components: {
    HeaderVue,
  },
};
</script>

<template>
  <div class="wrapper__container">
    <HeaderVue></HeaderVue>
  </div>
</template>

<style scoped>
.wrapper__container {
  width: 100%;
  height: 100vh;
  padding-top: 22px;
  background-color: #fafafa;
}
</style>
