<template>
  <div id="app">
    <HeaderCom></HeaderCom>
    <router-view></router-view>
    <FooterCom></FooterCom>
  </div>
</template>

<script>
import HeaderCom from "@/components/header";
import FooterCom from "@/components/footer";

export default {
  name: "App",
  components: {
    HeaderCom,
    FooterCom
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
