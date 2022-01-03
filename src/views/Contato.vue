<template>
  <div class="contatos">
    <div>
      <h1>Contatos</h1>
    </div>
    <div class="conteudo">
      <div class="lado-a">
        <h2>Entre em contato</h2>
        <ul>
          <li>WhatsApp: (95) 99156-0814</li>
          <li><a href="https://www.instagram.com/erick_sbatista/">Instagram</a></li>
          <li>G-Mail: dsantoserick@gmail.com</li>
          <li><a href="https://www.linkedin.com/in/erick-dos-santos-batista-04065010b/">Linkedin</a></li>
        </ul>

        <p>(Se preferir acesse pelo rodapé clicando nas redes.)</p>
      </div>
      <div class="lado-b">
        <h2>
          Você pode deixar seu feedbak, se desejar podemos marcar uma conversa
          onde você pode me conhecer melhor, afinal nada melhor do que uma
          conversa para expormos nossos pensamentos, ideias e planos para o
          futuro, nossos sonhos e desejos! Feliz 2022.
        </h2>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Contato",
};
</script>

<style scoped>
.contatos {
  min-height: 600px;
  background-color: rgb(122, 074, 145, 0.8);
  border-top: 20px solid rgb(249, 174, 86, 0.5);
  border-bottom: 20px solid rgb(249, 174, 86, 0.5);
  color: aliceblue;
  display: flex;
  align-content: center;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

h1 {
  border-bottom: 2px solid rgb(249, 174, 86, 0.5);
}

.conteudo {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  width: 100%;
  flex-direction: row;
  margin: 5rem 15rem;
}

.lado-a,
.lado-b {
  max-width: 50%;
}

.lado-a {
  margin-left: 5rem;
  max-width: 500px;
}
.lado-b {
  margin-right: 5rem;
  text-align: right;
  max-width: 500px;
}

h2 {
  justify-content: justify;
}

@media (max-width: 1200px) {
  .conteudo {
    display: block;
    text-align: center;
  }
  .lado-a,
  .lado-b {
    max-width: 100%;
    margin: 0;
  }
  ul {
    list-style: none;
  }

  ul li {
    margin: 0;
  }

  .conteudo .lado-a p {
    text-align: center;
    margin-bottom: 15px;
  }

  .lado-b {
    margin: 2rem;
    text-align: right;
    max-width: 100%;
    font-size: 0.8rem;
  }

  @media (max-width: 850px) {
    .lado-b {
    text-align: center;
  }
  }
}
</style>