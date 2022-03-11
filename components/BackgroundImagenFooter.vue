<template>
  <!-- Full Page Intro -->
  <footer
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
          <b-col sm="12" md="6" class="mb-5 mt-md-0 mt-5 text-white text-md-left p-2">
            <div class="text-center my-4 title-footer">
              CONTACTO COMERCIAL
            </div>
            <div class="text-center px-4">
              Cualquier información estamos para servirte. Ponte en contacto con nosotros,<br> cuéntanos tu necesidad y con gusto podemos agendar una video conferencia y/o una demostración
            </div>
            <div class="text-center px-4 mt-5">
              Cotizamos tu proyecto sin costo ajustándonos a tu necesidad y presupuesto
            </div>
          </b-col>
          <!--Grid column-->
          <!--Grid column-->
          <b-col sm="12" md="6" class="mb-5 mt-md-0 mt-5 text-white text-center text-md-left p-2">
            <div class="margin-icon">
              <div>
                Jorge Garzón Blancas
              </div>
              <div>
                <a>222 697 3664</a>
              </div>
              <div>
                jgarzon@spmit.com.mx
              </div>
              <div>
                Puebla, Pue. Mex.
              </div>
            </div>
          </b-col>
          <!--Grid column-->
        </b-row>
        <!--Grid row-->
      </b-col>
      <!-- Content -->
    </b-container>
    <!-- Mask & flexbox options-->
  </footer>
  <!-- Full Page Intro -->
</template>

<script>
export default {
  name: 'BackgroundImagenFooter',
  // eslint-disable-next-line vue/require-default-prop
  props: { coverImg: String }
}
</script>

<style>
.title-footer{
  font-weight: 700;
  font-size: 40px;
}
.margin-icon{
  margin-left: 25%;
}
</style>
