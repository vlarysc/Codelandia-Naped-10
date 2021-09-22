<template>
  <div id="app">
    <header class="main-header">
      <div id="header-container">
        <div id="nav">
          <div class="logo">
            <img src="./assets/img/Naped.svg" alt="Logo Naped" />
          </div>
          <div class="router-nav">
            <router-link class="menu-item" to="/">Home</router-link>
            <router-link class="menu-item" to="/series">Séries</router-link>
            <router-link class="menu-item" to="/filmes">Filmes</router-link>
            <router-link class="menu-item" to="/animes">Animes</router-link>
            <router-link class="menu-item" to="/games">Games</router-link>
          </div>
          <div class="btn"><button class="btn-nav">Minha conta</button></div>
        </div>
      </div>
    </header>
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  width: 90vw;
  margin-left: auto;
  margin-right: auto;
 /* border: 2px solid red; */
}

.btn {
  width: 10rem;
  height: 2rem;
  display: flex;
  justify-content: center;
 /* border: 2px solid red; */
}

.logo {
  width: 10rem;
  height: 2rem;
  display: flex;
  justify-content: center;
 /* border: 2px solid red; */
}

.main-header {
  width: 100%;
}

#header-container {
  max-width: 1440px;
}

.menu-items {
  list-style: none;
}

#nav.menu-item a:hover {
  opacity: 1;
  border-bottom: 2px solid #8257e6;
}

.btn-nav {
  width: 7rem;
  background-color: transparent;
  border: 2px solid #8257e6;
  color: #fefbfb;
  opacity: 0.8;
  font-size: 0.8rem;
  font-family: "lexend deca", sans-serif;
  border-radius: 15px;
  padding: 2px;
}

.btn-nav:hover {
  opacity: 1;
}

.router-nav {
  width: 40vw;
  display: flex;
  justify-content: flex-end;
  gap: 50px;
 /*border: 1px solid red; */
}

#nav {
  display: flex;
  justify-content: space-between;
  font-family: "Inter", sans-serif;
  padding: 30px;
  a {
    text-decoration: none;
    color: #cdcdcd;
    opacity: 0.8;

    &.router-link-exact-active {
      color: #fefbfb;
      border-bottom: 2px solid #8257e6;
    }
  }
  a:hover {
    opacity: 1;
    border-bottom: 2px solid #8257e6;
  }
}

@media screen and (min-width: 1440px) {
  .logo {
    width: 15rem;
    height: 2rem;
    display: flex;
    justify-content: flex-end;
  }
  .btn {
    width: 15rem;
    height: 2rem;
    display: flex;
    justify-content: flex-start;
  }
}
</style>
