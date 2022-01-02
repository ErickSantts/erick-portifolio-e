<template>
  <div class="container-footer">
    <a
      href="https://api.whatsapp.com/send?phone=+5595991560814"
      target="_black"
    >
      <img class="img-footer" src="/icones/whats-e.png" alt="" />
    </a>
    <a href="https://www.instagram.com/erick_sbatista/" target="_blank"
      ><img class="img-footer" src="/icones/instagram-e.png" alt=""
    /></a>
    <a
      href="https://www.linkedin.com/in/erick-dos-santos-batista-04065010b/"
      target="_blank"
      ><img class="img-footer" src="/icones/linkedin.png" alt=""
    /></a>
    <a href="mailto:dsantoserick@gmail.com">
      <img class="img-footer" src="/icones/email.png" alt="" />
    </a>
    <div class="footer texto">
      <strong>Erick S Batista &copy; 2021 | Desenvolvedor Front End </strong>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scorped>

.container-footer {
  background-color: #7a4a91;
  color: #f9ae56;
  min-height: 5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  border-top: 0.5rem solid rgb(999, 999, 999, 0.1);
  border-bottom: 0.5rem solid rgb(999, 999, 999, 0.1);
  width: 100%;
}

strong:hover {
  color: aliceblue;
}

.img-footer {
  background-color: rgb(999, 999, 999, 0.1);
  max-height: 40px;
  width: auto;
  border-radius: 1rem !important;
  transition: 0.8s;
  cursor: pointer;
}

.img-footer:hover {
  max-height: 50px;
  border: 3px solid #f9ae56;
  border-radius: 50%;
}

@media (max-width: 875px) {
  .container-footer {
    padding: 10px 0px;
    flex-wrap: wrap;
  }
}
</style>
