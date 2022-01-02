<template>
  <div class="introducao">
    <img id="introducao-img" src="/img/browser-s.png" alt="" />
    <h2>
      Morgana: Uma ferramenta baseada em comandos de voz para auxílio à
      Navegação em sites de internet para pessoas com limitaçõees nos membros
      superiores
    </h2>
    <hr />
    <hr />
    <h3>
      Tornar a web mais acessivel, usando comandos de voz foi uma ideia que
      surgiu durante a faculdade, uma experiencia incrivel que pode ser
      aperfeiçoada com passar do tempo.
    </h3>
  </div>
</template>

<script>
export default {
  name: "Introducao",
};
</script>
<style scoped>
.introducao {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
#introducao-img {
  max-width: 150px;
  width: auto;

  border-radius: 0% !important;
}

h2,
h3 {
  margin: 5px 15rem;
}

hr {
  text-align: justify;
  justify-content: justify;
  height: 2px;
  background-color: black;
  width: 70%;
}

@media (max-width: 1250px) {
  h2,
  h3 {
    margin: 5px 10rem;
  }
}

@media (max-width: 850px) {
  h2,
  h3 {
    margin: 2px 2rem;
  }
  #introducao-img {
  max-height: 150px;
  max-width: 150px;
  width: auto;
  height: auto;


  border-radius: 0% !important;
}
}
</style>