<template>
  <div>
    <NavBar />
    <BackgroundImagenLayout cover-img="url('/business-people-analyzing-statistics-financial.jpg')" />
    <SectionWhy />
    <h1 class="mt-5 text-center">
      Esto en NUXT
    </h1>
    <SideCard :valid="true" url="business-people-at-the-office.jpg " />
    <SideCard :valid="false" url="spm-cursos.jpg" />
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
