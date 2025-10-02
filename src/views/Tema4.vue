<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 ¿Cómo organizar y comprender la información de una investigación participativa?
    
    .row.mb-5.align-items-center
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema4/1.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
    
        .bg-color-4.tarjeta.p-5(data-aos="fade-left")
          p.mb-0 En una investigación participativa con comunidades campesinas, la organización y comprensión de la información recolectada no es tarea exclusiva del equipo investigador. Por el contrario, forma parte de un proceso colaborativo y reflexivo, donde tanto la comunidad como los investigadores analizan juntos lo que se ha observado, dicho y documentado. Este proceso puede estructurarse en cinco etapas principales:
    
    .bg-full-width.bg-color-19
      .px-4.px-md-5.pb-md-3
        .titulo-con-imagen.mb-5(data-aos="fade-right")
          .titulo-con-imagen__fondo
            img.titulo-con-imagen__imagen(src="@/assets/componentes/1.svg")
            h3.titulo-con-imagen__texto Tipo de información tomada en campo y otras fuentes
        
        p.mb-5 Para comenzar, es necesario identificar de dónde proviene la información y qué tipo de datos se han recolectado.

        TabsC.color-acento-contenido(data-aos="zoom-in").mb-5
          .py-3.py-md-4(titulo="Métodos participativos")
            .row.justify-content-center.align-items-center.p-4
              .col-lg-6.mb-4.mb-md-0.order-2
                h4 Métodos participativos
                p La información se obtiene mediante técnicas como entrevistas, encuestas, grupos focales, observación directa, talleres, cartografías, entre otros. En todos los casos, la comunidad campesina participa activamente y aporta sus conocimientos, vivencias y propuestas.
              .col-lg-5.order-1.mb-3.mb-lg-0
                figure
                  img(src='@/assets/curso/tema4/2.png', alt='Texto que describa la imagen')
          .py-3.py-md-4(titulo="Fuentes de información")
            .row.justify-content-center.align-items-center.p-4
              .col-lg-6.mb-4.mb-md-0.order-2
                h4 Fuentes de información
                p Se integran datos cualitativos (narrativas, testimonios, observaciones) y cuantitativos (cifras, estadísticas, mediciones). Ambas dimensiones son necesarias para construir una visión integral del contexto comunitario.
              .col-lg-5.order-1.mb-3.mb-lg-0
                figure
                  img(src='@/assets/curso/tema4/3.png', alt='Texto que describa la imagen')

        .titulo-con-imagen.mb-5(data-aos="fade-right")
          .titulo-con-imagen__fondo
            img.titulo-con-imagen__imagen(src="@/assets/componentes/1.svg")
            h3.titulo-con-imagen__texto Organización de la información

        p.mb-5 Una vez recopilada la información, el siguiente paso es clasificarla y ordenarla para facilitar su análisis.

        .bg-full-width.bg-fondo-slider.mb-5
          .p-4.p-md-5
            SlyderA(tipo="b").bg-color-white-1.p-4
              .row.align-items-center.p-4.p-md-5
                .col-lg-5.mb-3.mb-lg-0.order-2
                  figure
                    img(src="@/assets/curso/tema4/4.png")
                .col-lg-7.order-1.mb-3.mb-lg-0
                  h5 Clasificación temática
                  p Se agrupan los datos por categorías o ejes relevantes. Ejemplos: agricultura sostenible, salud comunitaria, participación, conflictos por tierra, tradiciones culturales, entre otros.
              .row.align-items-center.p-4.p-md-5
                .col-lg-5.mb-3.mb-lg-0.order-2
                  figure
                    img(src="@/assets/curso/tema4/5.png")
                .col-lg-7.order-1.mb-3.mb-lg-0
                  h5 Tabulación
                  p Los datos cuantitativos (como encuestas) se organizan en tablas que permiten visualizar fácilmente porcentajes, frecuencias o comparaciones. Las respuestas cualitativas se pueden agrupar según temas comunes.
              .row.align-items-center.p-4.p-md-5
                .col-lg-5.mb-3.mb-lg-0.order-2
                  figure
                    img(src="@/assets/curso/tema4/6.png")
                .col-lg-7.order-1.mb-3.mb-lg-0
                  h5 Codificación
                  p En la información cualitativa (entrevistas, diarios, observaciones), se aplican códigos o etiquetas que permiten identificar patrones, palabras clave o significados recurrentes en los relatos.
          
    .bg-full-width.bg-color-10
      .px-4.px-md-5.pb-md-3
        .titulo-con-imagen.mb-5(data-aos="fade-right")
          .titulo-con-imagen__fondo
            img.titulo-con-imagen__imagen(src="@/assets/componentes/1.svg")
            h3.titulo-con-imagen__texto Comprensión e interpretación colaborativa
        p.mb-5 En esta fase se busca dar sentido a la información recopilada, de forma conjunta entre investigadores y comunidad.

        .row.mb-5
          .col-lg-3.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema4/7.png", data-aos="zoom-in")
          .col-lg-9
            AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg-color-4")
              .div(titulo="Análisis conjunto")
                p El análisis se realiza en espacios participativos donde se escucha la interpretación local de los datos. Esto asegura que la lectura de la información sea contextualizada y culturalmente pertinente.
        
              .div(titulo="Reflexión comunitaria")
                p La comunidad tiene un conocimiento profundo de su realidad. Por eso, es fundamental que interprete los datos desde su experiencia y que esto se refleje en las conclusiones.
        
              .div(titulo="Triangulación")
                p Para validar los resultados, se comparan diferentes fuentes de información y distintos métodos aplicados. Por ejemplo, si una encuesta, una entrevista y una observación coinciden en señalar un problema, el hallazgo gana solidez.

        .titulo-con-imagen.mb-5(data-aos="fade-right")
          .titulo-con-imagen__fondo
            img.titulo-con-imagen__imagen(src="@/assets/componentes/1.svg")
            h3.titulo-con-imagen__texto Visualización de la información

        p.mb-5 Organizar y analizar no es suficiente: la información debe comunicarse de manera clara y accesible.
        
        .bg-full-width.bg-fondo-slider.mb-5
          .p-4.p-md-5
            SlyderA(tipo="b").bg-color-white-1.p-4
              .row.align-items-center.p-4.p-md-5
                .col-lg-5.mb-3.mb-lg-0.order-2
                  figure
                    img(src="@/assets/curso/tema4/8.png")
                .col-lg-7.order-1.mb-3.mb-lg-0
                  h5 Diagramas, mapas y gráficos
                  p Herramientas visuales que ayudan a representar de forma sencilla la distribución de problemas, recursos o actores clave. Por ejemplo, un mapa puede ubicar zonas con mayor escasez de agua o áreas en conflicto.
              .row.align-items-center.p-4.p-md-5
                .col-lg-5.mb-3.mb-lg-0.order-2
                  figure
                    img(src="@/assets/curso/tema4/9.png")
                .col-lg-7.order-1.mb-3.mb-lg-0
                  h5 Narrativas visuales
                  p Fotografías o vídeos tomados durante el proceso que ilustran situaciones concretas, complementan los testimonios y hacen más comprensibles los informes.
    
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.svg")
        h3.titulo-con-imagen__texto Informe final y retroalimentación
    
    p.mb-5 El cierre del proceso investigativo debe ser también participativo y útil para la comunidad.

    TabsA.color-acento-botones.mb-5
      .tarjeta.color-acento-botones--borde.p-4(titulo="Presentación de resultados")
        h4 Presentación de resultados
        .row
          .col-xl-6.order-lg-2
            figure
              img(src='@/assets/curso/tema4/10.png', alt='Texto que describa la imagen')
          .col-xl-6.order-lg-1
            p Se elabora un informe claro y comprensible, evitando lenguaje técnico innecesario. A menudo se incluyen ejemplos concretos, gráficos, citas textuales o ilustraciones que hagan más cercana la lectura.
      .tarjeta.color-acento-botones--borde.p-4(titulo="Acción comunitaria")
        h4 Acción comunitaria
        .row
          .col-xl-6.order-lg-2
            figure
              img(src='@/assets/curso/tema4/11.png', alt='Texto que describa la imagen')
          .col-xl-6.order-lg-1
            p Los resultados del proceso no deben quedarse solo en el papel. En muchas investigaciones participativas, los hallazgos se utilizan para diseñar proyectos, mejorar prácticas o gestionar soluciones colectivas, siempre desde las prioridades locales.
    
    p.mb-5 La organización y comprensión de la información en una investigación participativa no es un proceso técnico aislado, sino una práctica social, colectiva y contextual. A través de la clasificación, análisis conjunto y representación visual, se transforma la información en conocimiento útil para la comunidad, que puede ser utilizado para:

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema4/12.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-11.tarjeta.p-4.mb-3(data-aos="fade-left")
          div
            ul.lista-ul--color.mb-0
              li.mb-2.d-flex.bg-white.tarjeta.p-2
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Elaborar diagnósticos participativos.
              li.mb-2.d-flex.bg-white.tarjeta.p-2
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Hacer caracterizaciones de territorios o grupos.
              li.mb-2.d-flex.bg-white.tarjeta.p-2
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Gestionar soluciones a problemáticas locales.
              li.mb-2.d-flex.bg-white.tarjeta.p-2
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Aportar información para planes de desarrollo.
              li.mb-2.d-flex.bg-white.tarjeta.p-2
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Promover el uso consciente de datos cualitativos y cuantitativos aportados por la comunidad misma

    

</template>

<script>
export default {
  name: 'Tema4',
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
