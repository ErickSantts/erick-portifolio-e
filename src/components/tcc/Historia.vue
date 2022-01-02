<template>
  <div class="historia">
    <h1>Como surgiu a Morgana?</h1>
    <p>
      Ela nasceu com intuido de responder a seguinte questão: Como projetar uma
      extensão para o navegador Google Chrome que possa tornar uma página Web
      acessível a pessoas com dificuldades em usar mouse e teclado, adicionando
      comandos de voz como meio de entrada de dados? Vamos conhece-la, no video
      abaixo podemos ver seu funcionamento, o video está editado apenas para
      retirar o tempo que a Morgana leva para processar os comandos de voz, mas
      o conteudo sem edição pode ser acessado
      <a
        href="https://www.youtube.com/watch?v=P-1CRuPMtNI&feature=youtu.be"
        target="_blank"
      >
        clicando aqui</a
      >.
    </p>

    <iframe
      src="https://www.youtube.com/embed/W4sakwuSVX4"
      title="Morgana: Uma ferramenta baseada em comandos de voz para auxílio à
      Navegação em sites de internet para pessoas com limitaçõees nos membros
      superiores"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
    ></iframe>

    <h1>
      Agora que vimos ela funcionando vamos entrar um pouco mais em detalhes.
    </h1>
    <p>
      O objetivo principal deste trabalho foi desenvolver uma extensão para o
      navegador Google Chrome capaz de tornar uma página não projetada para
      receber comandos de voz, acessível por tal recurso, usando recursos
      presente na linguagem de programação JavaScript. Para isso foi criado o
      desafio de análisar diferentes ferramentas para reconhecimento de voz que
      possibilitaria o uso no desenvolvimento da extensão, então foi realizado o
      estudo de meios de mapeamento de sites para identificar menus e links que
      a pagina vier a possuir, assim pode ser identificado um padrão usado para
      construir os sites observando sua arvore, o que torna possivel unir o
      mapeamento ao comando de voz. O código-fonte deste projeto está disponível
      no repositório online
      <a href="https://github.com/ErickSantts/Morgana" target="_blank">
        GitHub</a
      >.
    </p>

    <div class="citacao">
      <p>
        <em>
          " A Morgana é um sonho, planejo aperfeiçoar meus conhecimento para um
          dia torna-lá realidade para as pessoas usarem em seu dia a dia."
        </em>
      </p>
      <h3>Erick S. Batista</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: "Historia",
};
</script>
<style scoped>
.historia {
  margin: 5rem 15rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

iframe {
    width: 560px;
    height: 315px;
  }

a:hover {
  color: #7a4a91;
  font-weight: bold;
}

iframe {
  margin: 4rem auto;
}
p {
  line-height: 1.9;
}
h1 {
  text-align: center;
}

.citacao {
  text-align: right;
}

.citacao > p {
  text-align: right;
  font-size: 1.2rem;
  margin-bottom: 1rem;
}

.citacao > h3 {
  font-size: 1rem;
}

@media (max-width: 1300px) {
  .historia {
    margin: 30px 100px;
  }
}

@media (max-width: 875px) {
  .historia {
    margin: 30px 50px;
  }
}
@media (max-width: 650px) {
  .historia {
    margin: 10px 20px;
  }
  iframe {
    width: 320px;
    height: 155px;
  }
}
</style>