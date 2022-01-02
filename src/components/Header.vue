<template>
  <header>
    <div class="container">
      <div class="logo"><router-link to="/">Home</router-link></div>
      <div class="menu-section" :class="{ on: menuExibir }">
        <div class="menu-toggle" @click="mudarStatus">
          <!-- :class="{ on: menuExibir }" -->
          <div class="um"></div>
          <div class="dois"></div>
          <div class="tres"></div>
        </div>
        <nav>
          <ul class="lista">
            <li class="item" @click="tornarStatusFalse">
              <router-link to="/tcc">Meu TCC</router-link>
            </li>

            <li class="item" @click="tornarStatusFalse">
              <router-link to="/sobre">Quem és</router-link>
            </li>
            <li class="item" @click="tornarStatusFalse">
              <router-link to="/contato">Contato</router-link>
            </li>
          </ul>
        </nav>
        <input type="checkbox" id="check" />
        <label for="check" class="checkbtn">
          <i class="fa fa-bars"></i>
        </label>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      menuExibir: false,
    };
  },
  methods: {
    mudarStatus() {
      this.menuExibir = !this.menuExibir;
      console.log(this.menuExibir);
    },
    tornarStatusFalse() {
      this.menuExibir = false;
    },
  },
};
</script>

<style>
.checkbtn {
  font-size: 30px;
  float: right;
  line-height: 80px;
  margin-right: 40px;
  cursor: pointer;
  display: none;
}

#check {
  display: none;
}
.container {
  display: flex;
  justify-content: space-between;
  background-color: #7a4a91;
  color: #f9ae56;
  height: 5rem;
  width: 100%;
  align-items: center;
  font-size: 1.2rem;
}
.logo {
  margin-left: 50px;
}
.log:hover {
  color: aliceblue;
}

.lista {
  margin-right: 50px;
  display: flex;
  list-style: none;
}

li {
  padding: 10px;
  margin-left: 20px;
}
a:active,
a:link,
a:checked,
a {
  color: #f9ae56;
  text-decoration-line: none;
}

a:hover {
  color: aliceblue;
}

@media (max-width: 600px) {
  nav {
    display: none;
  }
  .menu-section {
    cursor: pointer;
  }
  .um,
  .dois,
  .tres {
    transition: 0.8s;
    background-color: aliceblue;
    height: 5px;
    width: 100%;
    margin: 8px auto;
  }

  .menu-toggle {
    top: 20px;
    right: 20px;
    position: absolute;
    width: 40px;
    height: 20px;
    margin-right: 20px;
    cursor: pointer;
  }

  /*fullscrean */

  .menu-section.on {
    position: absolute;
    top: 0;
    left: 0;

    background-color: #7a4a91;

    width: 100%;
    height: 100vh;

    z-index: 10;

    display: flex;
    justify-content: center;
    align-items: center;
  }

  .menu-section.on nav {
    display: block;
  }

  .menu-section.on .menu-toggle .um {
    transform: rotate(45deg) translate(7px, 7px);
  }
  .menu-section.on .menu-toggle .dois {
    opacity: 0;
  }
  .menu-section.on .menu-toggle .tres {
    transform: rotate(-45deg) translate(11px, -11px);
  }

  .menu-section.on nav ul {
    text-align: center;
    display: block;
  }

  .menu-section.on nav ul li {
    transition-duration: 0.5s;
    font-size: 1.5rem;
    line-height: 4rem;
    display: block;
  }
}
</style>