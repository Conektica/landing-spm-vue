<template>
  <b-navbar toggleable="lg" type="dark" variant="dark" fixed="top">
    <div class="d-flex nav-centar">
      <b-navbar-brand href="#">
        <img src="/logo-spm.png" alt="SCS Projeckt Logo" class="navbar-logo">
      </b-navbar-brand>
      <b-navbar-nav>
        <b-nav-item class="nav-text font-italic">
          “Las actividades menos <br> importantes ocupan el 50% <br> de la jornada laboral”
        </b-nav-item>
      </b-navbar-nav>

      <b-navbar-toggle target="nav-collapse" />

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">
            Servicios
          </b-nav-item>
          <b-nav-item href="#">
            Contacto
          </b-nav-item>
          <b-nav-item href="#">
            Servicio SAP
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </div>
  </b-navbar>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style>
.navbar-logo {
  width: 200px;
}
.nav-text{
  font-size: 11px;
  line-height: 16px;
  color: #fff!important;
}
.nav-text:hover{
  text-decoration: none;
}
.nav-centar {
  max-width: 1200px;
  margin-left: auto;
  margin-right: auto;
}
</style>
