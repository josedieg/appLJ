<template>
  <div class="card">
    <div class="card-content">
      <div class="row valign-wrapper">
        <div class="col s1">
          <img src="https://materializecss.com/images/yuna.jpg" alt class="circle responsive-img">
          <!-- notice the "circle" class -->
        </div>
        <div class="col s11">
          <span
            class="black-text"
          >This is a square image. Add the "circle" class to it to make it appear circular.</span>
        </div>
      </div>
    </div>
    <div class="card-image">
      <img src="https://materializecss.com/images/sample-1.jpg">
      <span class="card-title">Card Title</span>
    </div>
    <div class="card-action">
      <a href="#">This is a link</a>
      <a href="#">This is a link</a>
    </div>
  </div>
</template>

<script>
import GridVue from "@/components/layouts/GridVue";

export default {
  name: "CardConteudoVue",
  props: [],
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
