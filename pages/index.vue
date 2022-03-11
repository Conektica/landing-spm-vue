<template>
  <div>
    <NavBar />
    <BackgroundImagenLayout cover-img="url('/business-people-analyzing-statistics-financial.jpg')" />
    <SectionWhy />
    <SideCard :valid="true" url="business-people-at-the-office.jpg " />
    <SideCard :valid="false" url="spm-cursos.jpg" />
    <BackgroundImagenNewLayout cover-img="url('/spm-asesoramos.jpg')" />
    <SectionMaterials />
    <SideRedCard :valid="false" url="desarollode-proyectos.jpg " />
    <br><br>
    <SideRedCard :valid="true" url="spm-capacitaciones.jpg " />
    <br>
    <IconsRibbon cover-img="url('/spm-colegas.jpg')" />
    <br><br>
    <BackgroundImagenBuilding cover-img="url('/edificio-SPM.jpg')" />
    <BackgroundImagenFooter cover-img="url('/spm-footer.jpg')" />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data () {
    return {
      title: 'SCS Projeckt'
    }
  },
  head () {
    return {
      title: this.title,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Esta es la descripcion de la pagina'
        }
      ],
      htmlAttrs: {
        lang: 'mx'
      }
    }
  }
}
</script>
