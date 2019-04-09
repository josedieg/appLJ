<template>
  <span>
    <header>
      <nav-bar-vue cor="green darken-1" logo="Site"></nav-bar-vue>
    </header>

    <main>
      <div class="container">
        <div class="row">
          <grid-vue tamanho="4">
            <card-menu-vue>
              <div class="row valign-wrapper">
                <div class="col s4">
                  <img
                    src="https://materializecss.com/images/yuna.jpg"
                    alt
                    class="circle responsive-img"
                  >
                  <!-- notice the "circle" class -->
                </div>
                <div class="col s8">
                  <span
                    class="black-text"
                  >This is a square image. Add the "circle" class to it to make it appear circular.</span>
                </div>
              </div>
            </card-menu-vue>
          </grid-vue>
          <grid-vue tamanho="8">
            <slot></slot>
          </grid-vue>
        </div>
      </div>
    </main>
    <footer>
      <footer-vue cor="green darken-1"></footer-vue>
    </footer>
  </span>
</template>

<script>
import NavBarVue from "@/components/layouts/NavBarVue";
import FooterVue from "@/components/layouts/FooterVue";
import GridVue from "@/components/layouts/GridVue";
import CardMenuVue from "@/components/layouts/CardMenuVue";

export default {
  name: "Site",
  components: {
    NavBarVue,
    FooterVue,
    GridVue,
    CardMenuVue
  }
};
</script>

<style>

</style>
