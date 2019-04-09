<template>
  <span>
    <header>
      <nav-bar-vue cor="green darken-1" logo="Site"></nav-bar-vue>
    </header>

    <main>
      <div class="container">
        <div class="row">
          <div class="col s4">Menu</div>
          <div class="col s8">
            <router-view></router-view>
          </div>
        </div>
      </div>
    </main>

    <footer-vue cor="green darken-1"></footer-vue>
  </span>
</template>

<script>
import NavBarVue from "@/components/layouts/NavBarVue";
import FooterVue from "@/components/layouts/FooterVue";

export default {
  name: "App",
  components: {
    NavBarVue,
    FooterVue
  }
};
</script>

<style>

</style>
