<template>
  <div class="container">
  <header>
      <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
      <div class="container-fluid">
        <router-link class="navbar-brand" to="/">Clothes Men's</router-link>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarCollapse"
          aria-controls="navbarCollapse"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav margin-navbar">
            <li class="nav-item ">
              <router-link class="nav-link" to="/">Inicio</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/nosotros">Nosotros</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/servicios">Servicios</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/contacto">Contáctanos</router-link>
            </li>

          </ul>
        </div>
      </div>
    </nav>
  </header>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
.margin-navbar{
  margin-left: auto;
}
</style>