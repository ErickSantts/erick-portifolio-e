<template>
  <div>
    <div class="cabecalho">
      <div class="efeito-ufrr">
        <div class="conteudo">
          <h4>Universidade Federal de Roraima</h4>
          <hr />
          <hr />
          <h2>UFRR</h2>
          <hr />
          <hr />
          <h4>Como entrei no mundo da tecnológia</h4>
        </div>
      </div>
    </div>
    <div class="conteudo-formacao">
      <h2>Sete anos inesqueciveis</h2>
      <h2>2013.2 - 2020.2</h2>
      <p>
        Quando entrei no curso de Ciência da Computação não entendia muito bem
        como funcionava, o maximo que tinha feito até então era um curso desses
        de informatica, onde o mais avançado era escrever algumas linhas de
        HTML. Meu primeiro choque foi ver que a grande maioria ali já programava
        e sabia o que era um algoritmo, eu estava caindo de paraquedas, e assim
        foi. Primeiro dia de aula, primeira aula, algoritmos. Que diaxo é
        algoritmos? Foi essa minha pergunta que me fiz, e foi ai que comecei a
        entender melhor o curso que estava fazendo, nunca tinha tirado uma nota
        vermelha na minha vida, primeiro semestre tirei um zero em pré-calculo
        (risos), mas também tirei um 10 em eletricidade básica porque precisa
        ter um equilibrio ai né?
        <br />
        Por incrivel que pareça comecei a entender mais sobre o mundo da
        computação, logo comecei a gostar de programar ao mesmo tempo que
        comecei a ter dificuldades, eita lasqueira! Começava as disciplinas do
        curso, de cara gostei de uma disciplina que era ministrada pelo pessoal
        de direito, Direito e Etica na Computação. Gostei mais discordo um
        pouquinho, pessoas que não são da area escrevendo leis sobre, não vai da
        muito certo eu pensei logo que comecei a estudar, logo depois comecei a
        entender melhor, mas confeço ainda discordo um pouco por mais que já não
        esteja bem fresco na memoria, mas vamos continuar, agora que ta ficando
        bom a história. Logo quando entrei, no meu segundo bimestre comecei a
        estagiar no NEaD (Núcleo de Ensino a Distância da Universidade Federal
        de Roraima), lá tive o contato com MOODLE e o JOOMLA, aprendi muito, não
        apenas a administrar os sistemas, mas a trabalhar em equipe e construir
        amizades verdadeiras, perdi muito da minha timidez ali, pois mininstrei
        capacitações, cursos e gravação de tutoriais relacionados a plataforma
        Moodle, sem duvidas foram passagens incriveis, de muito conhecimento e
        uma experiencia sem precedentes. Para finalizar, sim está acabando essa
        pequena historia, na verdade o resumo dela, porque ali tem historia! Meu
        tão esperado trabalho de conclusão de curso, mas vou deixar esse
        gostinho para vocês conhecerem melhor clicando aqui.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Ufrr",
};
</script>
<style scoped>
.cabecalho {
  width: 100%;
  background-image: url("/img/img-2.jpg");
  background-position: center;
  background-attachment: fixed;
  background-size: cover;
  height: 250px;
  display: flex;

  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.conteudo {
  background-color: rgb(122, 074, 145, 0.8);
  padding: 5px 150px;
  color: aliceblue;
  line-height: 3.5;
  transition: 0.8s;
  border-radius: 10px;
}
.conteudo:hover {
  color: #f9ae56;
  border-radius: 20px;
  padding: 20px 350px;
  line-height: 1.5;
  border: 5px solid aliceblue;
}
h4,
h2 {
  text-align: center;
}

.conteudo-formacao {
  margin: 5rem 15rem;
  line-height: 1.7;
}

@media (max-width: 600px) {

  .conteudo:hover {
  color: #f9ae56;
  border-radius: 20px;
  line-height: 1.5;
  border: 5px solid aliceblue;
}
}

</style>