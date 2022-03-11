<template>
  <!-- Full Page Intro -->
  <div
    :style="{backgroundImage:coverImg, backgroundRepeat:'no-repeat', backgroundSize:'cover', backgroundPosition: 'center center'}"
  >
    <!-- Mask & flexbox options-->
    <div class="mask">
      <br>
      <div class="text-center text-white title-img">
        SUMINISTRO DE MATERIALES
      </div>
      <div class="text-center text-white my-4 subTitle-img px-5">
        Hemos trabajado con empresas globales, multimarcas y locales. Contamos con una cartera de proveedores competitiva
      </div>
      <!-- Content -->
      <b-col class="container">
        <!--Grid row-->
        <br><br>
        <b-row class="mt-sm-5 mt-0">
          <!--Grid column-->
          <b-col sm="4" class="mb-5 mt-md-0 mt-5 text-white text-center text-md-left p-2">
            <b-img src="/lupa.svg" class="mx-auto d-flex" fluid alt="SPM" />
            <div class="mb-4 text-center mt-4 text-icon">
              <span class="font-weight-bold">Te ayudamos a identificar oportunidades mediante el cost breakdown</span> (incidencia de costos) de tu producto.
            </div>
          </b-col>
          <!--Grid column-->
          <!--Grid column-->
          <b-col sm="4" class="mb-5 mt-md-0 mt-5 text-white text-center text-md-left p-2">
            <b-img src="/grafica.svg" class="mx-auto d-flex" fluid alt="SPM" />
            <div class="mb-4 text-center mt-4 text-icon">
              <span class="font-weight-bold">Maximizamos ahorros</span> a través de análisis 80/20 de los gastos de la empresa.
            </div>
          </b-col>
          <!--Grid column-->
          <!--Grid column-->
          <b-col sm="4" class="mb-5 mt-md-0 mt-5 text-white text-center text-md-left p-2">
            <b-img src="/ayuda.svg" class="mx-auto d-flex" fluid alt="SPM" />
            <div class="mb-4 text-center mt-4 text-icon">
              <span class="font-weight-bold">Usamos índices de precios locales y globales</span> para manejar las negociaciones con tus proveedores.
            </div>
          </b-col>
          <!--Grid column-->
        </b-row>
        <!--Grid row-->
      </b-col>
      <!-- Content -->
    </div>
    <!-- Mask & flexbox options-->
  </div>
  <!-- Full Page Intro -->
</template>

<script>
export default {
  name: 'BackgroundImagenNewLayout',
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
