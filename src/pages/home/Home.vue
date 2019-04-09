<template>
<site>
<card-conteudo-vue></card-conteudo-vue>
</site>
</template>

<script>
import CardConteudoVue from "@/components/loja/CardConteudoVue";
import Site from "@/templates/Site"

export default {

  name: "Home",
  components:{
    CardConteudoVue,
    Site
  },
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
