<template>
  <!-- Full Page Intro -->
  <div
    :style="{backgroundImage:coverImg, backgroundRepeat:'no-repeat', backgroundSize:'cover', backgroundPosition: 'center center'}"
  >
    <!-- Content -->
    <b-col class="container">
      <!--Grid row-->
      <b-row class="mt-sm-5 mt-0">
        <!--Grid column-->
        <b-col sm="12" md="6" class="mt-md-0 my-5 text-md-left space-center">
          <div class="text-white">
            <span class="text-uppercase white-title">Consultoría</span>
            <div class="red-title">
              CAPACITACIÓN
            </div>
          </div>
          <div class="text-white question-text">
            ¿Observas áreas de mejora con tu equipo de cadena de suministro?
          </div>
          <div class="mb-4 text-white mt-4 text-build">
            En SCS Projeckt contamos con más de 10 años de experiencia en áreas como planeación, compras y logística. Damos soporte con capacitación, reporteo, estandarización de procesos, trato con proveedores y estrategias comerciales.
          </div>
        </b-col>
        <!--Grid column-->
        <!--Grid column-->
        <b-col sm="12" md="6" class="mb-5 mt-md-0 mt-5 text-white text-center text-md-left p-2">
          <br>
          <div class="text-white mt-4">
            <span class="text-uppercase white-title">Planeación</span>
            <div class="red-title">
              SAP MM (MATERIALS MANAGEMENT)
            </div>
            <div class="my-5">
              <ItemsList :itemsList="dataList" />
            </div>
            <span class="text-uppercase white-title">Compras</span>
            <div class="red-title">
              PROCUREMENT
            </div>
            <div class="my-5">
              <ItemsList :itemsList="dataListTwo" />
            </div>
          </div>
        </b-col>
        <!--Grid column-->
      </b-row>
    <!--Grid row-->
    </b-col>
    <!-- Content -->
  </div>
  <!-- Full Page Intro -->
</template>

<script>
export default {
  name: 'BackgroundImagenBuilding',
  // eslint-disable-next-line vue/require-default-prop
  props: { coverImg: String },
  data () {
    return {
      dataList: ['Creación y mantenimiento de estructuras de producto (BOM)', 'Aseguramiento de disponibilidad de materiales (MRP)', 'Análisis de demanda, productos ABC y Safety Stock', 'Gestión y análisis de inventarios', 'Reporte de inventarios proyectados (PSI)', 'Calificación y generación de programas de producción'],
      dataListTwo: ['SAP/ERP Proceso de compras de materias primas y MRO', 'Negociación de precios, incoterms, MOQ y tiempos de entrega', 'Aseguramiento de desempeño de proveedores', 'Análisis de PPV (Purchasing Price Variance)', 'Contratos de confidencialidad y acuerdos comerciales', 'Análisis de riesgos de mercado e impactos de precios', 'Auditorías de procesos de compras y proveedores']
    }
  }
}
</script>

<style>
.space-center{
  padding-left: 10%;
  padding-top: 10%;
}
.text-build{
  font-size: 16px;
  line-height: 25px;
}
.red-title{
  color: #DF0101;
  font-size: 20px;
}
.white-title{
  color: #fff;
  font-size: 35px;
  font-weight: 700;
}
.question-text{
  margin-top: 25px;
  font-weight: 500;
  font-size: 20px;
  line-height: 29px;
}
</style>
