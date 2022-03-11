<template>
  <b-container fluid>
    <b-row>
      <b-col id="col-1" />
      <b-col id="col-2">
        <a href="#">
          <h2>
            NUESTROS <br> SERVICIOS
            <svg
              class="arrowSVG"
              width="48"
              height="135"
              viewBox="0 0 48 135"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path d="M5 3L42 67.75L5 132.5" stroke="#DF0101" stroke-width="10" />
            </svg>
          </h2>
          <div class="text">
            SCS Projeckt cuenta con experiencia en varias empresas de manufactura de clase mundial. Somos efectivos y proactivos en los desarrollos de proyectos, con conocimientos en campos de cadena de suministro, y enfocados a entrega de objetivos.
          </div>
        </a>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: 'OurServices'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:wght@700&display=swap');
.container-fluid{
    padding: 0;
    margin: 40px 0;
}
#col-1{
    background-image: url('/services.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}
a:hover{
    text-decoration: none;
}
h2{
    font-family: 'Noto Sans', sans-serif;
    font-weight: 700;
    font-size: 50px;
    color: #FFFFFF;
    padding: 30px 20px 0 40px;
}
.arrowSVG {
    position: absolute;
    top: 25px;
    left: 350px;
    padding: 7px;
}
.text{
    font-size: 20px;
    font-family: 'Roboto', sans-serif;
    font-weight: 500;
    color: #FFFFFF;
    padding: 20px 225px 40px 40px;
}
#col-2{
    background-color: #494948;
}
</style>
