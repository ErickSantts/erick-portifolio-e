<template>
  <div class="formacao">
    <div class="item">
      <h1>Minha Formação</h1>
      <hr />
      <h3>
        Sou formado em Ciência da Computação pela UFRR <br />
        (Universidade Federal de Roraima)
      </h3>
    </div>
    <div class="item">
      <h1>Minhas Competências e habilidades</h1>
      <hr />
      <h3>
        Autoconhecimento <br />
        Capacidade de negociação <br />
        Comunicação <br />
        Flexibilidade <br />
        Resiliência <br />
      </h3>
    </div>
  </div>
</template>
<script>
export default {
  name: "Formacao",
};
</script>
<style scoped>
.formacao {
  min-height: 350px;
  display: flex;
  justify-items: center;
  align-items: center;
  justify-content: space-around;
  flex-wrap: wrap;
  margin: 30px;
}

@media (max-width: 1205px) {
  h3,
  h1 {
    text-align: center;
    margin: 10px 10px;
  }
  .item {
    margin: 30px;
    padding: 10px;
    text-align: center;
  }
}
</style>