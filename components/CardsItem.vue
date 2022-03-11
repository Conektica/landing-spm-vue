<template>
  <b-container fluid>
    <b-row class="justify-content-center">
      <b-col id="col-1" align="center" class="py-5">
        <IconText cover-img="award.svg" />
        <h2 class="titulo1">
          Proyectos de productividad
        </h2>
        <div class="text">
          <span>Cotizar es una tarea que requiere mucho recurso para dar seguimiento</span>, comparar y asegurar la calidad y especificación del producto. <br>

          SCS Projeckt lo hace por ti, <span>tenemos una gran cartera de proveedores y poder de negociación con el que podemos conseguir mejores precios.</span>
        </div>
      </b-col>
      <b-col id="col-2" align="center" class="py-5">
        <IconText cover-img="like.svg" />
        <h2 class="titulo2">
          Gestión de proyectos
        </h2>
        <div class="text-2">
          <span>En SCS Projeckt administramos tus proyectos de manera efectiva</span> con las áreas involucradas, dando el seguimiento que mereces y <span>consiguiendo la culminación de tus proyectos en el tiempo que necesitas.</span>
        </div>
      </b-col>
      <b-col id="col-3" align="center" class="py-5">
        <IconText cover-img="grafico.svg" />
        <h2 class="titulo3">
          Desarollo de productos
        </h2>
        <div class="text-2">
          Sabemos la importancia que tiene la calidad para tus clientes, es por eso que <span>SCS Projeckt te ayuda a desarrollar nuevos productos, apegándonos a los estándares de tu empresa.</span>
        </div>
      </b-col>
      <b-col id="col-4" align="center" class="py-5">
        <IconText cover-img="cuadro-de-dialogo.svg" />
        <h2 class="titulo4">
          Consultoría
        </h2>
        <div class="text-2">
          <span>¿Obsevas áreas de mejora con tu equipo de cadena de suministro?</span> En SCS Projeckt contamos con más de 10 años de experiencia en áreas como planeación, compras y logística. <span>Podemos apoyarte con capacitación, reporteo, estandarización de procesos, trato con proveedores y estrategias comerciales.</span>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: 'CardsItem'
}
</script>

<style scoped>
.container-fluid{
  margin-top: -40px;
}
#col-1{
  background: linear-gradient(140.82deg, #FE7F7F 6.73%, #DF0101 65.83%);
}
#col-3{
  background: #E5E5E5;
}
#col-1 h2{
  font-family: 'Roboto';
  font-weight: 700;
  color: #FFFFFF;
  font-size: 26px;
}
h2{
  font-family: 'Roboto';
  font-weight: 700;
  color: #000000;
  font-size: 26px;
}
h2.titulo1{
  margin-top: 40px;
}
h2.titulo2 {
    margin-top: 55px;
}
h2.titulo3,
h2.titulo4 {
    margin-top: 30px;
}
.text{
  font-family: 'Roboto';
  font-weight: 400;
  color: #FFFFFF;
  font-size: 20px;
}
.text-2{
  font-family: 'Roboto';
  font-weight: 400;
  color: #000000;
  font-size: 20px;
}
.text, .text-2 {
    margin-top: 40px;
}
span{
  font-weight: 600;
}
</style>
