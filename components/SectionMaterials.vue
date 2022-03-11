<template>
  <b-container fluid>
    <b-row>
      <b-col sm="12" md="6" class="pt-4">
        <div class="text-center font-weight-bold mb-5">
          <span style="font-size:28px">¿TIENES PROBLEMAS DE</span> <br> <span style="font-size:40px">SUMINISTRO?</span> <br><br><br><span style="font-size:32px">¿TUS PROVEEDORES</span> <br><span style="font-size:44px">INCREMENTARON</span> <br> <span style="font-size:27px"> DEMASIADO SUS PRECIOS?</span>
        </div>
      </b-col>
      <b-col sm="12" md="6" class="pt-4" style="background: #E5E5E5;">
        <div class="pl-4 font-weight-bold" style="font-size:20px">
          Te ayudamos con materiales como:
        </div>
        <b-row class="pl-4">
          <b-col sm="6">
            <ul class="list-red mt-4">
              <li>Corrugado</li>
              <li>Resina</li>
              <li>Papel</li>
              <li>Acero</li>
              <li>Cobre</li>
            </ul>
          </b-col>
          <b-col sm="6">
            <ul class="list-red mt-4">
              <li>Fasteners</li>
              <li>Estampados</li>
              <li>Casting</li>
              <li>Plástico</li>
              <li>Madera</li>
            </ul>
          </b-col>
        </b-row>
        <b-row class="my-5">
          <a class="btn btn-red mx-auto d-flex my-2">CONTÁCTANOS</a>
        </b-row>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: 'SectionMaterials'
}
</script>

<style scoped>
ul {
  list-style: none;
}
li{
  font-size:25px;
  font-weight: 500;
}
.list-red > li::before{
  content: "\2022";
  color: #DF0101;
  padding: .4rem;
  line-height: 17px;
  font-size: 35px;
  vertical-align: -4px;
}
.btn-red{
 background-color: #DF0101;
 color: #fff;
 font-size: 25px;
 border-radius: 15px;
 padding-left: 60px;
 padding-right: 60px;
}
</style>
