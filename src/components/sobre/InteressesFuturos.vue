<template>
  <div>
    <div class="degrade"></div>
    <div class="cabecalho-interesses">
      <img src="/img/img-sobre.png" alt="" />
    </div>
    <div class="conteudo-interesses">
      <h2>Meus interesses e planos para o futuro</h2>
      <hr />
      <hr />
      <transition name="fade">
        <p >
          Meus interesses e planos para o futuro Atualmente pretendo continuar
          como desenvolvedor Java, mas estou aberto para novas oportunidades,
          uma area grande interesse que tenho é a acessibilidade web, por isso
          meu trabalho de conclusão de curso foi desenvolvido com esse tema.
          Para desenvolver esse trabalho fiz uso de JavaScript, sendo assim
          outro enteresse que possuo, me aprofundar futuramente e quem sabe
          trocar Java por JavaScritp, atualmente não tenho me dedicado tanto a
          novas tecnologias por ainda está digamos “aprendendo” Java, mas logo
          logo sem dúvidas dominar o desenvolvimente web será uma realidade. Uma
          certeza que tenho, não sou o melhor programador, mas também nada me
          impede de ser. Então, vamos por as ideias e sonhos em pratica e só
          vamos parar quando realizar, e dai ir pro proximo e proximo em um loop
          eterno, só não podemos parar!
        </p>
      </transition>
    </div>
  </div>
</template>

<script>
export default {
  name: "interessesFuturos",

};
</script>

<style scoped>
/* .degrade {
  background-image: linear-gradient(0.25turn, aliceblue, #7a4a91, aliceblue);
  height: 100px;
  width: 100%;
  transition-duration: 2s;
  padding: 10px 0px;
}

.degrade:hover{
    background-image: linear-gradient(0.25turn,#7a4a91,#7a4a91,#7a4a91);
} */
.cabecalho-interesses {
  text-align: center;
}
.cabecalho-interesses > img {
  max-width: 200px;
  height: 200px;
  text-align: center;
}

.conteudo-interesses {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin: 0rem 15rem 0rem 15rem;
  line-height: 1.7;
}

hr {
  margin-top: 5px;
  width: 100%;
  height: 1px;
  background: #ff0;
}

p {
  background-color: rgb(aliceblue, aliceblue, aliceblue, 0.8);
  background-origin: center;
  transition: 0.8s ease;
  margin-bottom: 20px;
}
@media(max-width: 1300px){
  .conteudo-interesses{
    margin: 20px 10%;
  }

  .cabecalho-interesses img{
    margin-top: 40px;
  }
}
@media (max-width: 600px) {

  .conteudo-interesses{
    margin: 10px 10%;
  }

  .cabecalho-interesses img{
    margin-top: 20px;
  }
}
</style>