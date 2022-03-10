<template>
  <b-container>
    <h1 class="my-4 font-weight-bold">
      ¿POR QUÉ SCS PROJECKT?
    </h1>
    <!--Grid row-->
    <b-row>
      <b-col sm="12" md="6" class="p-4 font-weight-bold">
        <div>
          Estadísticamente hablando, las actividades menos importantes ocupan el 50% de la jornada laboral aproximadamente. Esta mala gestión del tiempo es causada por diferentes factores como:
        </div>
        <div>
          <ul class="my-5 list-red">
            <li>Acumulación de tareas</li>
            <li>Falta de organización</li>
            <li>Comunicación ineficaz</li>
          </ul>
        </div>
        <div>
          SCS Projeckt está enfocada 100% en la necesidad del cliente, consiguiendo mayor productividad y eficiencia.
        </div>
      </b-col>
      <b-col sm="12" md="6" class="p-4">
        <div>
          <ul class="my-3 list-gray">
            <li>Mejor toma de decisiones<br><span>Claridad y consistencia</span></li>
            <li>Menos plazos ajustados<br><span>Calendarios y horarios predeterminados</span></li>
            <li>Mayor calidad de trabajo<br><span>Correcta gestión de tiempos y seguimiento</span></li>
          </ul>
        </div>
      </b-col>
    </b-row>
    <!--Grid row-->
    <!--Grid row-->
    <b-row>
      <b-col sm="12" class="text-center paragraph-center p-2">
        <span>Ponte en contacto con nosotros, queremos conocer tu necesidad</span>
        <div :style="{color:'#DF0101'}" class="font-weight-bold">
          En SCS PROJECKT nuestro único objetivo es ayudar a las empresas a ser más productivas
        </div>
        <span>Cotizamos sin costo y brindamos la propuesta más competitiva</span>
      </b-col>
    </b-row>
    <!--Grid row-->
  </b-container>
</template>

<script>
export default {
  name: 'SectionWhy'
}
</script>

<style scoped>
ul {
  list-style: none;
}
.list-red > li::before{
  content: "\2022";
  color: #DF0101;
  padding: .2rem;
  line-height: 17px;
  font-size: 35px;
  vertical-align: -4px;
}
.list-gray > li{
    font-weight: 700;
    font-size: 20px;
    margin: 19px 0px 19px 0px;
}
.list-gray > li::before{
  content: "";
  display: inline-block;
  width: 20px;
  height: 20px;
  margin-right: 0.7rem;
  background-image: url(/cir-gray.svg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
}
.list-gray > li > span{
  padding-left: 23px;
  color: #DF0101;
}
.paragraph-center{
  font-size: 32px;
}
.paragraph-center > span {
  color: #000;
  font-weight: 600;
}
</style>
