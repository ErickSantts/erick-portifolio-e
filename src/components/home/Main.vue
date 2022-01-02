<template>
  <div>
    <div class="main">
      <div class="text-main">
        <h2>Erick Batista</h2>
        <h1>Bem Vindo ao meu Portifólio</h1>
        <h3>Conheça um pouco de quem eu sou, fique a vontade!</h3>
      </div>
    </div>
    <div class="linha-5"></div>
    <div class="linha-4"></div>
    <div class="linha-3"></div>
    <div class="linha-2"></div>
    <div class="linha-1"></div>
    <div class="linha-0"></div>
    <QuemSou />
    <div class="linha-0"></div>
    <div class="linha-1"></div>
    <div class="linha-2"></div>
    <div class="linha-3"></div>
    <div class="linha-4"></div>
    <div class="linha-5"></div>
    <ResumoProfissional />
  </div>
</template>
<script>
import QuemSou from "./QuemSou.vue";
import ResumoProfissional from "./ResumoProfissional.vue";
export default {
  name: "Main",
  components: { QuemSou, ResumoProfissional },
};
</script>
<style>
.main {
  width: 100%;
  background-image: url("/img/img.jpg");
  background-attachment: fixed;
  background-size: cover;
  height: 500px;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-position: bottom;
}
.linha-5 {
  width: 100%;
  height: 6px;
  margin-top: 10px;
  background-color: #7a4a91;
}
.linha-4 {
  width: 100%;
  height: 5px;
  margin-top: 10px;
  background-color: #7a4a91;
}
.linha-3 {
  width: 100%;
  height: 4px;
  margin-top: 10px;
  background-color: #7a4a91;
}
.linha-2 {
  width: 100%;
  height: 3px;
  margin-top: 10px;
  background-color: #7a4a91;
}
.linha-1 {
  width: 100%;
  height: 2px;
  margin-top: 10px;
  background-color: #7a4a91;
}
.linha-0 {
  width: 100%;
  height: 1px;
  margin-top: 10px;
  background-color: #7a4a91;
}

.text-main {
  text-align: center;
  max-width: 500px;
  height: auto;
  padding: 10px;
  border-radius: 10px;
  background-color: rgb(122, 074, 145, 0.8);
  color: #f9ae56;
  transition: 0.8s;
}

.text-main:hover {
  -webkit-filter: drop-shadow(15px 10px 15px rgba(87, 6, 124, 0.8));
  filter: drop-shadow(15px 10px 15px rgba(71, 4, 102, 0.8));
  cursor: default;
}

@media (max-width: 530px) {
  .text-main {
    display: flex;
    flex-direction: column;
  }
}
</style>