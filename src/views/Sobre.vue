<template>
  <div class="about">
    <Cabecalho />
    <Formacao />
    <Ufrr />
    <InteressesFuturos/>
  </div>
</template>
<script>
import Formacao from "../components/sobre/Formacao.vue";
import Cabecalho from "../components/sobre/Cabecalho.vue";
import Ufrr from "../components/sobre/Ufrr.vue";
import InteressesFuturos from "../components/sobre/InteressesFuturos.vue";
export default {
  components: {
    Cabecalho,
    Formacao,
    Ufrr,
    InteressesFuturos,
  },
};
</script>
