<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span 1
      h1 Toma de decisiones  en los jóvenes

    p(data-aos="slide-down") Con frecuencia el error común de los jóvenes emprendedores es que no son conscientes de que todas y cada una de las acciones que realizan, tienen un precio y por supuesto, generan unos resultados o consecuencias.  

    .row.justify-content-start.align-items-center(data-aos="slide-down") 
      .col-lg-10.p-color-1-t3.py-3.px-3
        .row.justify-content-start.align-items-center 
          .col-lg-9.ps-5  
            p(data-aos="slide-down").p-left El éxito de un emprendedor joven está determinado en gran medida por la calidad de las decisiones que ha tomado y la posibilidad que estas le han ofrecido para explorar nuevas oportunidades.
              br
              br
              | Entonces, ¿qué se puede hacer para tomar una decisión adecuada?, para resolver esta pregunta conocerás el proceso de toma de decisiones; este proceso es una guía que te permitirá analizar el problema o la situación, generar y evaluar diferentes opciones para finalmente seleccionar la mejor opción, entre varias alternativas posibles.

    .row.justify-content-end.align-items-center(data-aos="slide-down") 
      .col-lg-4.p-0.m-0.d-none.d-lg-block
        img.img-t.t1-m-top(data-aos="zoom-in")(src='@/assets/ilustraciones/img3.png', alt='')

    separador(data-aos="slide-left")
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.1 Proceso de toma de decisiones de los jóvenes

    img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/img4.png', alt='') 
    .row.justify-content-center.align-items-center.m-t1-top(data-aos="slide-down")
      .col-lg-11.sup
        .bg-img-1-t1.p-4
          p.mb-0 Aunque existen muchas teorías y esquemas acerca del proceso que realizan todos los seres humanos para tomar una decisión, el esquema realizado por Martínez (2014) reúne los elementos más importantes. Visualiza el siguiente video antes de profundizar en cada paso de la toma de decisiones.  
    figure.mt-5(data-aos="slide-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/K2aTksfIG9s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen) 

    .row.justify-content-center.align-items-center.mt-5(data-aos="slide-down") 
      .col-lg-8.title-t1-color
        h4.text-center.text-white.mb-0.p-4 Ahora profundicemos en cada paso de la toma de decisiones a partir del infográfico

    .bg-img-2-t1.py-5.bg-top(data-aos="slide-down")        
      ImagenInfografica.color-primario.py-5
        template(v-slot:imagen)
          figure
            img(src='@/assets/ilustraciones/img7.svg', alt='')

        .tarjeta.color-acento-botones.p-3(x="11.4%" y="50%" numero="")
          .row.justify-content-center.align-items-center 
            .col-lg-8        
              .h5.mb-2 Definir el problema
            .col-lg-auto
              img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/01.svg', alt='') 
          p Identificar el problema o el objetivo que se pretende alcanzar, proponiendo unas metas claras y medibles. 

        .tarjeta.color-acento-botones.bg-2.p-3(x="31%" y="50%" numero="")
          .row.justify-content-center.align-items-center 
            .col-lg-8        
              .h5.mb-2 Analizar el problema
            .col-lg-auto
              img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/02.svg', alt='') 
          p Recopilar toda la información necesaria para analizar de manera objetiva. Precisar la información más relevante, se puede recopilar la información elaborando una lista de chequeo.           

        .tarjeta.color-acento-botones.bg-3.p-3(x="50%" y="50%" numero="")
          .row.justify-content-center.align-items-center 
            .col-lg-8        
              .h5.mb-2 Evaluar las alternativas
            .col-lg-auto
              img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/03.svg', alt='') 
          p Generar y evaluar todas las alternativas y consecuencias de las mismas. Existen técnicas de solución de problemas como lo son la lluvia de ideas, diagrama causa - efecto, matriz DOFA, entre otras, que pueden ayudarnos a generar alternativas de valor. Cuantas más personas participen en el proceso más aspectos se tendrán en cuenta y más ideas podremos obtener.   

        .tarjeta.color-acento-botones.bg-4.p-3(x="69.3%" y="50%" numero="")
          .row.justify-content-center.align-items-center 
            .col-lg-8        
              .h5.mb-2 Elegir las alternativas
            .col-lg-auto
              img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/04.svg', alt='') 
          p Elegir la mejor alternativa después del ejercicio de evaluación y análisis. Sin embargo, ten en cuenta  que el error es posible y este se debe asumir como  una oportunidad de mejorar para los procesos futuros.   

        .tarjeta.color-acento-botones.bg-5.p-3(x="88.6%" y="50%" numero="")
          .row.justify-content-center.align-items-center 
            .col-lg-8        
              .h5.mb-2 Aplicar la decisión
            .col-lg-auto
              img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/05.svg', alt='') 
          p Poner en práctica la decisión tomada. Para llevar a cabo la decisión, es necesario planificar cómo se ejecutará y qué recursos se requieren para implementarla.             

</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
