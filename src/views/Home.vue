<template>
  <Main />
</template>

<script>
import Main from "../components/home/Main.vue";
import QuemSou from "../components/home/QuemSou.vue";
import ResumoProfissional from "../components/home/ResumoProfissional.vue";
export default {
  name: "Home",
  components: {
    Main,
    QuemSou,
    ResumoProfissional,
  },
};
</script>