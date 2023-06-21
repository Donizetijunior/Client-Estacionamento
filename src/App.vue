<template>
  <nav class="navbar navbar-expand-lg nav-bar-color">
    <div class="container-fluid">
      <ul class="navbar-nav">
        <li class="nav-item"><router-link to="/" class="router-link-nav">Home</router-link></li>
        <li class="nav-item"><router-link to="/listar-marca" class="router-link-nav">Marca</router-link></li>
        <li class="nav-item"><router-link to="/listar-modelo" class="router-link-nav">Modelo</router-link></li>
        <li class="nav-item"><router-link to="/listar-veiculo" class="router-link-nav">Veiculo</router-link></li>
        <li class="nav-item"><router-link to="/listar-condutor" class="router-link-nav">Condutor</router-link></li>
        <li class="nav-item"><router-link to="/listar-movimentacao" class="router-link-nav">Movimentação</router-link></li>
        <li class="nav-item"><router-link to="/listar-configuracao" class="router-link-nav">Configuração</router-link></li>
      </ul>
    </div>
  </nav>
  <router-view/>
</template>

<style lang="scss">



@import "~/node_modules/bootstrap/scss/bootstrap";
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css");

#app {
  font-family: -apple-system, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif ,Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  max-width: 500px;
  height: 100vh;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  flex-direction: column;
  
 
}

li {
  padding: 12px;

  a {
    font-weight: bold;
    color: #7e4107;

    &.router-link-exact-active {
      color: #83b893;
    }
  }
}

.router-link-nav{
  text-decoration: none;
  color: #000000;
  text-align: center;
}

.nav-bar-color{
  background-color: #478049;
}

body{
  background-color: #000000;
  margin: 0px;
  padding: 0px;
}
  nav {
  background-color:none;
  position: fixed;
  top: 0px;
  width: 550px;
  height: 55px;   
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 25px;
  border-bottom: #35abe1 solid;
  
  
}
*{
  padding: 0;
  margin: 0;
  border: 0;
  box-sizing: border-box;
}
</style>
