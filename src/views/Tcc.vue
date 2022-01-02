<template>
  <div>
    <Introducao />
    <Historia />
  </div>
</template>
<script>
import Introducao from "../components/tcc/Introducao.vue";
import Historia from "../components/tcc/Historia.vue";
export default {
  components: {
    Introducao,
    Historia,
  },
  name: "Tcc",
};
</script>