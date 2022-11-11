<template>
  <div id="app">
    <nav class="navbar navbar-expand navbar-dark bg-success">
      <router-link to="/" class="navbar-brand">>F&F COMPANY</router-link>
      <div class="navbar-nav mr-auto">
        <li class="nav-item">
          <router-link to="/productos" class="nav-link">Productos</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/categorias" class="nav-link">Categorías</router-link>
        </li>
      </div>
    </nav>

    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>

<script>
export default {
  name: "app"
};
</script>
<style>
  .rutas{
    position: relative;
    padding: 5px 5px;
    border: none;
    outline: none;
    background-color:lightblue;
    color: white
  }
  .nav-link:hover{
    background-color:lightgreen
  }
</style>