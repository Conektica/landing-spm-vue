<template>
  <!-- Full Page Intro -->
  <div
    :style="{backgroundImage:coverImg, backgroundRepeat:'no-repeat', backgroundSize:'cover', backgroundPosition: 'center center'}"
  >
    <!-- Mask & flexbox options-->
    <div class="mask dark-gradient margin-cover-img">
      <!-- Content -->
      <div class="container">
        <!--Grid row-->
        <b-row class="mt-5">
          <!--Grid column-->
          <b-col sm="12" md="6" class="mb-5 mt-md-0 mt-5 text-white text-center text-md-left">
            <h6 class="mb-3 margin-text-p text-center">
              Te ayudamos a mitigar los impactos ocasionados por los incrementos de precio en materias primas, desabastos y gastos logísticos con nuestro servicios de <b>Solución en Cadena de Suministros y Gestión de poyectos empresariales</b>
            </h6>
            <div class="title-img my-4">
              Nuestro objetivo es darte 5% de AHORRO anual
            </div>
          </b-col>
          <!--Grid column-->
          <!--Grid column form-->
          <b-col sm="12" md="6" class="mb-4">
            <!--Form-->
            <div class="card mt-4">
              <div class="card-body">
                <!--Body-->
                <div class="md-form">
                  <label for="form3" class="active">Nombre</label>
                  <input
                    type="text"
                    class="white-text form-control"
                  >
                </div>
                <div class="md-form">
                  <label for="form2" class="active">Correo electrónico</label>
                  <input
                    type="email"
                    class="white-text form-control"
                  >
                </div>
                <div class="md-form">
                  <label for="form4">Teléfono</label>
                  <input
                    type="number"
                    class="white-text form-control"
                  >
                </div>
                <div class="md-form">
                  <label for="form4">Ciudad</label>
                  <input
                    type="text"
                    class="white-text form-control"
                  >
                </div>
                <div class="md-form">
                  <label for="form4">Nombre de la empresa</label>
                  <input
                    type="text"
                    class="white-text form-control"
                  >
                </div>
                <div class="text-right mt-4">
                  <button class="btn btn-danger">
                    Enviar
                  </button>
                </div>
              </div>
            </div>
            <!--/.Form-->
          </b-col>
          <!--Grid column form-->
        </b-row>
        <!--Grid row-->
        <!--Grid row-->
        <b-row class="row my-5">
          <b-col class="container">
            <br>
          </b-col>
        </b-row>
        <!--Grid row-->
      </div>
      <!-- Content -->
    </div>
    <!-- Mask & flexbox options-->
  </div>
  <!-- Full Page Intro -->
</template>

<script>
export default {
  name: 'BackgroundImagenLayout',
  props: { coverImg: String }
}
</script>

<style>
.dark-gradient{
  background: linear-gradient(180deg, rgba(0, 0, 0, 0.799) 53.83%, rgba(255, 255, 255, 0) 97.39%);
}
.margin-cover-img{
  margin-top: 82px;
}
.margin-text-p{
  margin-top: 50px;
  line-height: 30px;
  font-size: 20px;
  text-shadow: 4px 4px 3px rgba(0, 0, 0, 0.5);
}
.title-img{
    color: #DF0101;
    font-weight: 800;
    font-size: 40px;
    line-height: 47px;
    text-shadow: 5px 4px 4px rgba(0, 0, 0, 0.5);
}
</style>
