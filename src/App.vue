<template>
  <div>
    <nav-bar cor="green darken-1" logo="Site"></nav-bar>
    <router-view/>
  </div>
</template>

<script>
import NavBar from "@/components/layouts/NavBar"

export default {
  name: "App",
  components:{
    NavBar
  }
};
</script>

<style>

</style>
