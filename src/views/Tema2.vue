<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span 2
      h1 Análisis de alternativas y riesgos

    img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/img8.png', alt='') 
    .row.justify-content-center.align-items-center.m-t1-top(data-aos="slide-down")
      .col-lg-11.sup
        .bg-img-1-t1.p-4
          p.mb-0 La generación de alternativas estimula la búsqueda de información y un análisis profundo de la situación. En ocasiones, la falta de información lleva a tomar decisiones equivocadas pues no se tiene una visión completa de la situación, siendo complejo desarrollar alternativas desde una visión sesgada.      
    .row.justify-content-center.align-items-center.mt-5(data-aos="slide-down") 
      .col-lg-10
        .cajon.color-acento-contenido.p-4.mb-4
          p.mb-0 Si bien en la mayoría de las ocasiones no es fácil identificar todas las opciones posibles, cuantas más alternativas se generen es más probable obtener una que resulte significativamente satisfactoria. 

    separador(data-aos="slide-left")
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.1 Herramientas para generar alternativas  

    .bg-img-t2.py-5(data-aos="slide-down") 
      .row.justify-content-center.align-items-center.bg-top(data-aos="slide-down") 
        .col-lg-10    
          ImagenInfografica.color-primario.py-5
            template(v-slot:imagen)
              figure
                img.img-t.img-a(src='@/assets/ilustraciones/img10.svg', alt='')

            .tarjeta.color-acento-botones.bg-5.p-3(x="32.7%" y="59%" numero="")
              h4.text-center.mb-0 Lluvia de ideas             
            .tarjeta.color-acento-botones.bg-3.p-3(x="48.1%" y="65.7%" numero="")   
              h4.text-center.mb-0 Diagrama de Ishikawa
            .tarjeta.color-acento-botones.bg-2.p-3(x="65%" y="59%" numero="")
              h4.text-center.mb-0 Análisis DOFA
      .row.justify-content-center.align-items-center.mt-5(data-aos="slide-down") 
        .col-lg-10.color-p-gray
          h4.text-center.mb-0.p-4 A continuación, se verán algunas de las herramientas más utilizadas para generar alternativas.
    hr
    AcordionA(data-aos="fade-right")(tipo="b" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center.align-items-center(titulo="1. Lluvia de ideas") 
        .row.justify-content-center.align-items-start         
          .col-lg-4(data-aos="fade-right")
            img(data-aos="zoom-in")(src='@/assets/ilustraciones/img11.png', alt='')        
          .col-lg-8(data-aos="fade-left")
            p.mt-5 Esta técnica generalmente es utilizada cuando se busca llegar a consensos o tomar decisiones en grupo. Pues permite aprovechar la participación de los integrantes y generar la mayor cantidad de opciones; además motiva a un razonamiento mayor y más imaginativo (Ionos, 2018).
        .bg-img-1-t2.px-5
          .row.justify-content-center.align-items-start.mx-2         
            .col-lg-12.pb-5.d-none.d-lg-block           
              .row.justify-content-end.align-items-center.color-p-gray.mx-2.row-top-t2         
                .col-lg-8(data-aos="fade-right")
                  p.mb-0.py-4 La lluvia de ideas se concibe de manera grupal, coordinado por un moderador, responsable de crear clima de trabajo positivo para desarrollar la actividad y estimular la participación de los asistentes.

          .row.justify-content-end.align-items-center.color-p-gray.d-block.d-lg-none
            .col-lg-8(data-aos="fade-right")
              p.mb-0.p-4 La lluvia de ideas se concibe de manera grupal, coordinado por un moderador, responsable de crear clima de trabajo positivo para desarrollar la actividad y estimular la participación de los asistentes. 

          h4.text-center.mt-5 Proceso de lluvia de ideas 
          ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta
                span a
              p La persona que conduce la sesión (moderador) debe explicar el problema, situación o la oportunidad que se presenta y dar a conocer las principales reglas:

          .row.justify-content-center.align-items-stretch.mt-5
            .col-lg-3.mb-4.mb-xl-0
              .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img
                    img.img-t.img-a.mt-4(data-aos="zoom-in")(src='@/assets/ilustraciones/img13.svg', alt='')
                  .tarjeta-flip__contenido.py-5.px-3           
                    p.mb-0.text-center Ofrecer tantas ideas como sea posible, ser creativo.

            .col-lg-3.mb-4.mb-xl-0
              .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img
                    img.img-t.img-a.mt-4(data-aos="zoom-in")(src='@/assets/ilustraciones/img14.svg', alt='')
                  .tarjeta-flip__contenido.py-5.px-3             
                    p.mb-0.text-center No criticar las ideas de los demás o discutir sobre la utilidad de estas.

            .col-lg-3.mb-4.mb-sm-0
              .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img
                    img.img-t.img-a.mt-4(data-aos="zoom-in")(src='@/assets/ilustraciones/img15.svg', alt='')
                  .tarjeta-flip__contenido.py-5.px-3            
                    p.mb-0.text-center Aplazar el juicio, toda idea es válida y no deben ser rechazadas.   

            .col-lg-3.mb-4.mb-sm-0
              .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img
                    img.img-t.img-a.mt-4(data-aos="zoom-in")(src='@/assets/ilustraciones/img16.svg', alt='')
                  .tarjeta-flip__contenido.py-5.px-3          
                    p.mb-0.text-center Combinar, adaptar, y transformar las ideas para generar una nueva.                                   

          .row.justify-content-center.align-items-center.mt-5(data-aos="fade-right")         
            .col-lg-6
              ol.lista-ol--cuadro
                li 
                  .lista-ol--cuadro__vineta
                    span b
                  p Agrupar y ubicar en orden jerárquico. 
                li 
                  .lista-ol--cuadro__vineta
                    span c
                  p Priorizar las alternativas más promisorias e interesantes, se puede solicitar a los participantes dar una puntuación, las que obtienen más votos son discutidas en mayor profundidad, las demás son descartadas.  
                li 
                  .lista-ol--cuadro__vineta
                    span d
                  p Analizar las causas y los efectos de las alternativas priorizadas y cómo estas influyen en la solución del problema u objetivo, para finalmente definir la alternativa a ejecutar.                                                  
            .col-lg-6
              img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/img17.png', alt='') 

        .bg-img-2-t2.px-5.pb-5
          .row.justify-content-center.align-items-center.mt-5.pb-5(data-aos="fade-right")         
            .col-lg-5
              h4 Ejemplo aplicado
              p Una empresa de transporte de viajeros por carretera está interesada en seleccionar la mejor alternativa para resolver el problema de las largas esperas frente a los expositores de información. El equipo encargado empezó realizando una lluvia de ideas sobre las posibles soluciones a las esperas.
              p La pregunta planteada es ¿cómo mejorar el problema de las largas esperas frente a las taquillas de información?
              p Después de llevar a cabo la lluvia de ideas los resultados fueron estos:

            .col-lg-7
              .tabla-a.color-primario.mb-5 
                table
                  thead
                    tr
                      th.w-t.t-color Alternativa propuesta
                      th.w.t-color.text-center Votos

                  tbody
                    tr
                      td.w-t Un mayor número de informadores en las taquillas 
                      td.w.text-center 2 
                    tr
                      td.w-t Folletos con información de las rutas 
                      td.w.text-center 3 
                    tr
                      td.w-t Capacitar a los informadores para una rápida atención 
                      td.w.text-center 2 
                    tr
                      td.w-t Implementar un sistema de turnos digitales
                      td.w.text-center 3 
                    tr
                      td.w-t Implementar un sistema de pantallas para mostrar la información del transporte 
                      td.w.text-center 4 
                    tr
                      td.w-t Aumentar el salario de los informadores para que presten un servicio más eficiente 
                      td.w.text-center 1

        .row.justify-content-center.align-items-center.row-top-t2(data-aos="fade-right")         
          .col-lg-11
            img.img-t.img-a.mt-5(data-aos="zoom-in")(src='@/assets/ilustraciones/img19.png', alt='') 
            .row.justify-content-center.align-items-center.m-t1-top(data-aos="slide-down")
              .col-lg-11.sup
                .bg-img-1-t1.p-4
                  p.mb-0 De acuerdo con las opciones propuestas y la votación de los participantes, se podría concluir que implementar un sistema de pantallas, resulta ser la mejor decisión; no obstante, se debe estudiar más esta alternativa, estará de acuerdo en que se puede generar altos costos económicos que deriven en un incremento en el valor de los pasajes.   

        .row.justify-content-center.align-items-center.mt-5(data-aos="fade-right")         
          .col-lg-10
            img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/img20.svg', alt='') 
        hr.mt-4
      .row.justify-content-center.align-items-center(titulo="2. Diagrama de ishikawa")
        .bg-img-3-t2.mb-5
          .row.justify-content-center.align-items-center         
            .col-lg-4
              img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/img21.png', alt='') 
            .col-lg-8
              P También conocido como el diagrama de espina de pescado o diagrama de causa y efecto. Permite identificar el problema u oportunidad y visualizar las causas que lo generan.

              P Es empleado para facilitar el análisis de los problemas y encontrar soluciones factibles a partir de las causas identificadas. Se centra en el por qué.
              .row.justify-content-center.align-items-center
                .col-lg-11
                  .list.mt-3
                    .list__item
                        .list__item__icon
                            img(src="@/assets/ilustraciones/V1.svg", alt="")
                    .list__txt 
                        span En la cabeza del diagrama se escribe el problema o efecto que pretendemos analizar.
                  .list.mt-2
                    .list__item
                        .list__item__icon
                            img(src="@/assets/ilustraciones/V1.svg", alt="")
                    .list__txt 
                        span En las espinas o líneas de los lados se escribirán las causas que se considera producen el problema o situación.
                  .list.mt-2
                    .list__item
                        .list__item__icon
                            img(src="@/assets/ilustraciones/V1.svg", alt="")
                    .list__txt 
                        span A cada causa se le incluyen subcausa que afectan la causa y el efecto.
        p Algunas recomendaciones para la utilización de esta herramienta son:

        .row.justify-content-center.align-items-start.mt-5
          .col-lg-auto
            img.img-t.img-a(src='@/assets/ilustraciones/1.svg', alt='')
          .col-lg-10.bg-gray.px-3.py-4
            p.mb-0 Mantener la calma si no se conoce alguna causa, el mismo análisis evidenciará causas que no habían sido previstas. Si existe alguna dificultad se pueden categorizar las causas.

        .row.justify-content-center.align-items-start.mt-3
          .col-lg-auto
            img.img-t.img-a(src='@/assets/ilustraciones/2.svg', alt='')
          .col-lg-10.bg-gray.px-3.py-4
            p.mb-0 Aplazar el juicio simplemente anotar sin calificar su factibilidad.

        .bg-img-4-t2.p-5
          h4 Ejemplo aplicado
          p Una fábrica de zapatos ha identificado una disminución constante en la producción, se reúne el equipo encargado para identificar cuáles son las causas principales que están generando esta situación, para lo cual se realiza una lluvia de ideas, posteriormente se realiza la jerarquización de las causas y se plasman en el siguiente diagrama de ishikawa.
          img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img24.svg', alt='')

        hr.mt-4

      .row.justify-content-center.align-items-center(titulo="3. Análisis DOFA")
        .bg-img-3-t2
          .row.justify-content-center.align-items-center
            .col-lg-5
              img.img-t.img-a(src='@/assets/ilustraciones/img25.png', alt='')
            .col-lg-7
              p Esta herramienta permite realizar un análisis interno (debilidades y fortalezas) y externo (oportunidades y amenazas) teniendo en cuenta todos los factores involucrados en una decisión (Visión industrial, 2017).
              p Al hacer una revisión de la situación actual, promueve la toma de decisiones a través de diferentes alternativas, para definir el escenario futuro que se quiere obtener.
              img.img-t.img-a(src='@/assets/ilustraciones/img26.svg', alt='')
        .bg-img-4-t2.p-5
          h4 Ejemplo aplicado
          p En la fábrica de zapatos que analizamos anteriormente se decidió realizar una matriz DOFA, analizando las fortalezas, debilidades, oportunidades y amenazas de la empresa, las cuales se plasmaron en el siguiente gráfico:  
          .row.justify-content-center.align-items-stretch.mt-5
            .col-lg-3.mb-4.mb-xl-0
              .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img
                    img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img29.svg', alt='')
                    h5.text-center.text-white.mt-3 Fortalezas
                  .tarjeta-flip__contenido.p-3       
                    p.mb-0.text-center Fortalezas                  
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Capacidad de adaptación
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Trayectoria en el mercado
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Innovación en diseños
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span.mb-0 Calidad y confiabilidad del producto

            .col-lg-3.mb-4.mb-xl-0
              .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img
                    img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img30.svg', alt='')
                    h5.text-center.text-white.mt-3 Debilidades
                  .tarjeta-flip__contenido.p-3          
                    p.mb-0.text-center Debilidades 
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Personal sin capacitación
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Protocolos y procedimientos no estandarizados
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Servicio al cliente deficiente
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span No se mide el clima organizacional

            .col-lg-3.mb-4.mb-sm-0
              .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img
                    img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img31.svg', alt='')
                    h5.text-center.text-white.mt-3 Oportunidades
                  .tarjeta-flip__contenido.p-3         
                    p.mb-0.text-center Oportunidades 
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Tratados de libre comercio
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Adquisición de implementación de tecnología
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Programas de capacitación para mejorar el servicio.

            .col-lg-3.mb-4.mb-sm-0
              .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img
                    img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img32.svg', alt='')
                    h5.text-center.text-white.mt-3 Amenazas
                  .tarjeta-flip__contenido.p-3          
                    p.mb-0.text-center Amenazas 
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Incremento de la competencia
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span Incremento en los precios de la materia prima
                    .list.mt-2
                      .list__item
                          .list__item__icon
                              img(src="@/assets/ilustraciones/V1.svg", alt="")
                      .list__txt 
                          span La demanda es estacional

</template>
<script>
export default {
  name: 'Tema2',
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
