<template>
  <!-- Full Page Intro -->
  <div
    :style="{backgroundImage:coverImg, backgroundRepeat:'no-repeat', backgroundSize:'cover', backgroundPosition: 'center center'}"
  >
    <!-- Mask & flexbox options-->
    <b-container fluid>
      <!-- Content -->
      <b-col class="container">
        <!--Grid row-->
        <br><br>
        <b-row class="mt-sm-5 mt-0">
          <!--Grid column-->
          <b-col sm="6" md="3" class="mb-5 mt-md-0 mt-5 text-white text-center text-md-left p-2">
            <IconText coverImg="foco.svg" :titleValid="true" titleText="DISEÑO" pText="Concepto de producto Especificación funcional Clientes" />
          </b-col>
          <!--Grid column-->
          <!--Grid column-->
          <b-col sm="6" md="3" class="mb-5 mt-md-0 mt-5 text-white text-center text-md-left p-2">
            <IconText coverImg="pc.svg" :titleValid="true" titleText="DEFINICIÓN" pText="Recursos materiales Recursos profesionales Objetivos Escenarios Riesgos" />
          </b-col>
          <!--Grid column-->
          <!--Grid column-->
          <b-col sm="6" md="3" class="mb-5 mt-md-0 mt-5 text-white text-center text-md-left p-2">
            <IconText coverImg="calendario-spm.svg" :titleValid="true" titleText="GESTIÓN" pText="Definición de alcances y fechas Planeación y organización Trabajo en conjunto NPD Cronogramas Actividades y responsables definidos" />
          </b-col>
          <!--Grid column-->
          <!--Grid column-->
          <b-col sm="6" md="3" class="mb-5 mt-md-0 mt-5 text-white text-center text-md-left p-2">
            <IconText coverImg="carrito.svg" :titleValid="true" titleText="IMPLEMENTACIÓN" pText="Especificación técnica Engineering Sample Lot (ESL) Manufacturing Sample Lot (MSL) Production Part ApProval Porcess (PPAP) Producción Serie" />
          </b-col>
          <!--Grid column-->
        </b-row>
        <!--Grid row-->
      </b-col>
      <!-- Content -->
    </b-container>
    <!-- Mask & flexbox options-->
  </div>
  <!-- Full Page Intro -->
</template>

<script>
export default {
  name: 'IconsRibbon',
  // eslint-disable-next-line vue/require-default-prop
  props: { coverImg: String }
}
</script>

<style>
.title-img{
  padding-top: 40px;
  font-weight: 600;
  font-size: 43px;
}
.subTitle-img{
  font-weight: 600;
  font-size: 35px;
}
.text-icon{
  font-size: 26px;
  line-height: 30px;
}
</style>
