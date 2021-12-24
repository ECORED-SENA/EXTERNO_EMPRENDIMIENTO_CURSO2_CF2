<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .bg-img-t1.pb-5
      .row.justify-content-center.align-items-start         
        .col-lg-4(data-aos="fade-right")
          img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/img2.png', alt='')        
        .col-lg-8(data-aos="fade-left")
          p.mt-5 Los grandes jóvenes emprendedores se enfrentan constantemente a  tomar decisiones basados en el análisis y observaciones. Con el desarrollo de este tema podrás conocer la importancia de la toma de decisiones, cómo la elección entre dos o más alternativas puede traer consecuencias positivas o negativas en tu vida cotidiana, así como, potencializar o afectar el éxito de tu emprendimiento.
      .row.justify-content-center.align-items-start.mx-2         
        .col-lg-12.pb-5.d-none.d-lg-block           
          .row.justify-content-end.align-items-center.color-p-gray.mx-2.row-top      
            .col-lg-8(data-aos="fade-right")
              p.mb-0.py-4 También conocerás el proceso de toma de decisiones y cuáles son los pasos o fases que te permitirán optar por la alternativa óptima, fortaleciendo así sus habilidades y capacidades para evaluar y validar la información en el momento de tomar una decisión. 

    .row.justify-content-end.align-items-center.color-p-gray.d-block.d-lg-none
      .col-lg-8(data-aos="fade-right")
        p.mb-0.p-4 También conocerás el proceso de toma de decisiones y cuáles son los pasos o fases que te permitirán optar por la alternativa óptima, fortaleciendo así sus habilidades y capacidades para evaluar y validar la información en el momento de tomar una decisión.                        




</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass">
.row-top
  margin-top: -150px
@media (max-width: 1300px)
  .row-top
    margin-top: -90px !important
</style>
