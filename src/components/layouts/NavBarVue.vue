<template>
  <nav :class="cor">
    <div class="nav-wrapper container">
      <a :href="url || '#'" class="brand-logo">{{ logo }}</a>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li>
          <a href="sass.html">Sass</a>
        </li>
        <li>
          <a href="badges.html">Components</a>
        </li>
        <li>
          <a href="collapsible.html">JavaScript</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBarVue",
  props: ["logo", "url", "cor"],
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
