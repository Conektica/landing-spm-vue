<template>
  <b-container fluid>
    <!--Grid row-->
    <b-row>
      <!--Grid column-->
      <b-col v-if="valid" sm="12" md="6" style="background: #E5E5E5;" class="p-5">
        <div class="my-5 title-card">
          WORKOUT
        </div>
        <div class="font-weight-bold">
          La técnica llamada workout o workshop consiste en realizar reuniones entre determinadas personas, en las que los asistentes aportan, en pie de igualdad, conocimientos, impresiones, ideas y preguntas acerca del tema sobre el que se discute en la reunión.
        </div>
      </b-col>
      <!--Grid column-->
      <!--Grid column-->
      <b-col sm="12" md="6" class="whithout-right-space whithout-left-space">
        <b-img class="w-100 h-100" :src="url" />
      </b-col>
      <!--Grid column-->
      <!--Grid column-->
      <b-col v-if="!valid" sm="12" md="6" style="background: linear-gradient(140.82deg, #FE7F7F 6.73%, #DF0101 65.83%);" class="p-5">
        <div class="my-5 title-card text-white">
          OBJETIVO
        </div>
        <div class="font-weight-bold text-white">
          Reunir a un equipo multidisciplinario para obtener ideas de ahorros, con el fin de generar un libro de proyectos anuales.
          <p class="mt-4">
            Objetivo – Ahorros del 5% anual
          </p>
        </div>
      </b-col>
      <!--Grid column-->
    </b-row>
    <!--Grid row-->
  </b-container>
</template>

<script>
export default {
  name: 'SideCard',
  props: { valid: Boolean, url: String }
  /* created () {
    // eslint-disable-next-line no-console
    console.log(this.valid)
  } */
}
</script>

<style scoped>
.whithout-right-space {
    padding-right: 0px !important;
}
.whithout-left-space {
    padding-left: 0px !important;
}
.title-card{
  font-weight: 700;
  font-size: 40px;
}
</style>
