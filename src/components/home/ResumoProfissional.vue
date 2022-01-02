<template>
  <div class="container-resumo">
    <div class="header-resumo">
      <h1>Resumo Profissional</h1>
      <h2>
        Analista de Sistemas Web no Governo do Estado de Roraima – Boa Vista, RR
      </h2>

      <h2>Janeiro de 2021 – Até o atual momento.</h2>
    </div>
    <div class="text-resumo">
      <p>
        No Governo do Estado de Roraima estamos constantemente dando manutenção
        aos sistemas de controle e gestão. Sistemas como Educarr, Acompanharr,
        Autorizarr, Cesta da Família, entre outros. São sistemas de várias
        secretarias do governo onde mantemos atualizados e implementamos
        soluções de acordo com as necessidades do governo. Nesse momento
        trabalho dentro dos sistemas abaixo.
        <br />* Educarr – É um sistema voltado para educação, onde tem-se todas
        as escolas cadastradas para que seja um sistema de gestão da secretaria
        de educação do estado, onde se tem controle de todos os alunos do
        estado, como imigrantes, brasileiros, alunos atrasados, adiantados por
        ultimo foi implementado o sistema de correção de fluxo e as notas
        especiais durante a pandemia, entre outras demandas do governo que
        aparecem todos os dias, como geração de relatórios usando integração com
        Jasper, seja ele de notas, ou de alunos de uma escola, são diversos já
        implementados para uma melhor gestão. <br />* Acompanhar – Esse sistema
        é torna possível o acompanhamento dos projetos de todas as secretarias,
        onde os secretarias cadastram cada projeto e ação realizada pela mesma,
        tendo controle então sobre cada projeto, ação desse projeto e os
        responsáveis por tal. <br />* Cesta da Família – Cesta é um sistema que
        gerencia programas sociais, como o que leva seu proprio nome, Cesta da
        Família. Nele e realizado o cadastro de todas os beneficiários do
        programa social, onde se tem controle por exemplo de quem recebeu o
        beneficio, quem não recebeu, quem vai receber etc.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "ResumoProfissional",
};
</script>
<style scoped>
.container-resumo {
  background-color: #7a4a91;
  color: #f9ae56;
}
.header-resumo {
  padding-top: 3rem;
  align-items: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
  width: 100%;
  text-align: center;
}
.text-resumo {
  padding: 3rem 10rem;
}

@media (max-width: 875px) {
  .header-resumo {
    margin: 30px 0px;
  }
  .text-resumo {
    padding: 3rem 5rem;
  }
}

@media (max-width: 530px) {
  .header-resumo {
    margin: 0px 0px;
  }
  .text-resumo {
    padding: 2rem 2rem;
  }
}
</style>