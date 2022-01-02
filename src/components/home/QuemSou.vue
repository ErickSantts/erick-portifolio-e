<template>
  <div>
    <div class="flex-container">
      <img class="avatar" src="/img/transferir.jpg" />

      <div class="quem-sou-container">
        <h1>Quem sou?</h1>
        <p>
          Me chamo Erick, sou formado em Ciência da Computação pela Universidade
          Federal de Roraima, fui estagiário no Núcleo de Educação a Distância
          na Universidade Federal de Roraima, gerenciando o site do núcleo de
          educação a distancia (Joomla) e a plataforma de educação a distancia
          (Moodle), ministrei palestras e mini cursos sobre o gerenciamento da
          plataforma. Durante meu trabalho de conclusão de curso implementei uma
          extensão para navegador que possibilita pessoas com limitações em seus
          membros superiores pudessem acessar páginas web utilizando comando de
          voz, usando tecnologias como JavaScript e Node.js.

          <br />
          No atual trabalho pelo governo do Estado de Roraima desenvolvo novas
          funcionalidades utilizando Java junto ao Prime Faces e JSF, adotando
          padrão MVC. Sou um profissional no começo da carreira sem muita
          experiência e em busca de novos desafios. A busca por conhecimento e
          novas experiências me faz está disposto a agarrar novas oportunidades.
          Possuo bom conhecimento em lógica de programação e meu conhecimento em
          Java vem se aprofundando com passar do tempo, atualmente me considero
          programador Júnior e todos os dias tenho pequenas novas experiências
          com a linguagem. Uma linguagem que tenho interesse é o JavaScrit, no
          qual desenvolvi meu trabalho de conclusão de curso, mas que nunca me
          aprofundei na linguagem.
        </p>
      </div>
    </div>
    <div class="btn-classe">
      <router-link to="/sobre"
        ><button class="saiba-mais-btn">
          Clique, e saiba mais.
        </button></router-link
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "QuemSou",
};
</script>

<style>
.flex-container {
  display: flex;
  align-content: center;
  align-items: center;
  margin: 30px 100px;
}
.quem-sou-container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: center;
  flex-wrap: wrap;
  margin: 20px 50px;
}

.avatar {
  max-width: 177px;
  max-height: 150px;
  width: auto;
  height: auto;
  border-radius: 50%;
}

p {
  margin-top: 20px;
  text-align: justify;
}

.saiba-mais-btn {
  background-color: #7a4a91;
  width: auto;
  height: auto;
  padding: 1rem 2rem;
  border-style: none;
  border-radius: 1rem;
  color: #f9ae56;
  cursor: pointer;
  transition: 0.8s;
}

.saiba-mais-btn:hover {
  background-color: transparent;
  color: #7a4a91;
  border: 0.1rem solid #7a4a91;
  font-weight: 900;
}

.btn-classe {
  display: flex;
  justify-content: center;
  margin-bottom: 2rem;
}

@media (max-width: 1300px) {
  .flex-container {
    display: flex;
    align-content: center;
    align-items: center;
    margin: 30px 100px;
    flex-direction: column;
  }
}

@media (max-width: 875px) {
  .flex-container {
    margin: 30px 0px;
  }
}
</style>