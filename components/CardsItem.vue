<template>
  <b-container fluid>
    <b-row>
      <b-col class="py-5 gradient-box text-center" sm="6" md="3">
        <IconText cover-img="award.svg" />
        <h2 class="titulo1 text-white">
          Proyectos de productividad
        </h2>
        <div class="textW">
          <span>Cotizar es una tarea que requiere mucho recurso para dar seguimiento</span>, comparar y asegurar la calidad y especificación del producto.
        </div>
        <div class="textW2">
          SCS Projeckt lo hace por ti, <span>tenemos una gran cartera de proveedores y poder de negociación con el que podemos conseguir mejores precios.</span>
        </div>
      </b-col>
      <b-col class="py-5 text-center" sm="6" md="3">
        <IconText cover-img="like.svg" />
        <h2 class="titulo2">
          Gestión de proyectos
        </h2>
        <div class="textB">
          <span>En SCS Projeckt administramos tus proyectos de manera efectiva</span> con las áreas involucradas, dando el seguimiento que mereces y <span>consiguiendo la culminación de tus proyectos en el tiempo que necesitas.</span>
        </div>
      </b-col>
      <b-col class="py-5 text-center box-gray" sm="6" md="3">
        <IconText cover-img="grafico.svg" />
        <h2 class="titulo3">
          Desarollo de productos
        </h2>
        <div class="textB">
          Sabemos la importancia que tiene la calidad para tus clientes, es por eso que <span>SCS Projeckt te ayuda a desarrollar nuevos productos, apegándonos a los estándares de tu empresa.</span>
        </div>
      </b-col>
      <b-col class="py-5 text-center" sm="6" md="3">
        <IconText cover-img="cuadro-de-dialogo.svg" />
        <h2 class="titulo4">
          Consultoría
        </h2>
        <div class="textB">
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
.gradient-box{
  background: linear-gradient(140.82deg, #FE7F7F 6.73%, #DF0101 65.83%);
}
.box-gray{
  background: #E5E5E5;
}
.container-fluid > h2{
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
  padding-top: 40px;
}
h2.titulo2 {
  padding-top: 40px;
}
h2.titulo3,
h2.titulo4 {
  padding-top: 30px;
}
.textW, .textW2{
  font-family: 'Roboto';
  font-weight: 400;
  color: #FFFFFF;
  font-size: 20px;
}
.textB{
  font-family: 'Roboto';
  font-weight: 400;
  color: #000000;
  font-size: 20px;
}
.textW, .textB {
  padding-top: 40px;
}
.textW2{
  padding-top: 20px;
}
span{
  font-weight: 600;
}
</style>
