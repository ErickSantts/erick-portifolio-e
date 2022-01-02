<template>
  <div class="cabecalho">
    <div class="efeito-surgir">
      <h1>Minha história, quem eu sou hoje.</h1>
      <hr />
      <h2>
        Vou contar um pouco mais sobre minha trajetoria até aqui, meus
        interesses e meus planos para o futuro.
      </h2>
    </div>
  </div>
</template>

<script>
export default {
  name: "Cabecalho",
};
</script>

<style scoped>
.cabecalho {
  width: 100%;
  background-image: url("/img/img-2.jpg");
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  height: 500px;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}

.efeito-surgir {
  transition: 0.8s;
  background-color: rgb(122, 074, 145, 0.8);
  color: #f9ae56;
  background-attachment: fixed;
  padding: 10px;
  border-radius: 10px;
}

.efeito-surgir:hover {
  background-color: rgb(122, 074, 145, 0.8);
  padding: 50px;
  border-radius: 20px;
  color: aliceblue;
  cursor: default;
}


</style>