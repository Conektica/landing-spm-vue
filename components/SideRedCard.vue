<template>
  <b-container fluid>
    <!--Grid row-->
    <b-row>
      <!--Grid column-->
      <b-col v-if="valid" sm="12" md="6" class="p-5 red-box">
        <div class="text-white font-red-box p-5" style="text-align:right">
          En <b>SCS Projeckt administramos tus proyectos</b> de manera efectiva  con las áreas involucradas dando el seguimiento que mereces y <b>consiguiendo la culminación de tus proyectos en el tiempo que necesitas.</b>
        </div>
      </b-col>
      <!--Grid column-->
      <!--Grid column-->
      <b-col sm="12" md="6" class="whithout-right-space whithout-left-space">
        <b-img class="w-100 h-100" :src="url" />
      </b-col>
      <!--Grid column-->
      <!--Grid column-->
      <b-col v-if="!valid" sm="12" md="6" class="p-5 red-box">
        <div class="text-white font-red-box p-5">
          Sabemos la importancia que tiene la calidad para tus clientes, es por eso que <b>SCS Projeckt te ayuda a desarrollar tus nuevos productos,</b> apegándonos a los estándares de tu empresa.
        </div>
      </b-col>
      <!--Grid column-->
    </b-row>
    <!--Grid row-->
  </b-container>
</template>

<script>
export default {
  name: 'SideRedCard',
  props: { valid: Boolean, url: String }
  /* created () {
    // eslint-disable-next-line no-console
    console.log(this.valid)
  } */
}
</script>

<style scoped>
.red-box{
    background-color: #DF0101;
}
.font-red-box{
  font-size: 23px;
}
.whithout-right-space {
    padding-right: 0px !important;
}
.whithout-left-space {
    padding-left: 0px !important;
}
</style>
