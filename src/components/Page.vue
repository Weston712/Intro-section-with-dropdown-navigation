<script>
import HeaderVue from "./Header.vue";
import MaincontentVue from "./Maincontent.vue";
export default {
  components: {
    HeaderVue,
    MaincontentVue,
  },
};
</script>

<template>
  <div class="wrapper__container">
    <HeaderVue></HeaderVue>
    <MaincontentVue></MaincontentVue>
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
