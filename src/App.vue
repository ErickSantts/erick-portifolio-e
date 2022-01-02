<template>
  <Header />
  <transition
    mode="out-in"
    enter-active-class="animated rubberBand"
    leave-active-class="animated rollOut"
  >
    <router-view />
  </transition>
  <Footer />
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
export default {
  components: {
    Header,
    Footer,
  },
};
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Anonymous+Pro:ital@1&family=Raleway:wght@200&display=swap");
* {
  margin: 0px;
  padding: 0px;
  font-family: "Raleway", sans-serif;
  font-weight: 900;
}
</style>
