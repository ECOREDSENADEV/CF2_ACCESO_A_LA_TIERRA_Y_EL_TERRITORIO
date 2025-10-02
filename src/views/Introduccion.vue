<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.mb-5.align-items-center
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/intro/1.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") La investigación en comunidades campesinas no solo busca recopilar datos, sino comprender la realidad de quienes habitan y transforman el territorio. A través de metodologías participativas, este proceso se convierte en una herramienta para identificar necesidades, fortalecer la organización social y proyectar soluciones colectivas que respondan a los retos del entorno.
    
        .row.align-items-start
          .col-lg-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/intro/2.svg", style="max-width: 190px").mx-auto
          .col-lg
            div.bg-color-4.p-4.tarjeta
              p.mb-0 En este contexto, el componente formativo Escuchemos a las comunidades campesinas promueve el uso de técnicas cualitativas y cuantitativas que permiten recoger la voz de la comunidad. Métodos como la cartografía social, los grupos focales, los talleres, el análisis FODA y los diarios de campo se articulan para generar un conocimiento situado, respetuoso y útil, que rescata los saberes locales y los combina con herramientas técnicas.
    

    .row.align-items-center
      .col-lg-auto.mb-3.mb-lg-0
        img(src="@/assets/curso/intro/3.svg", style="max-width: 90px").mx-auto
      .col-lg
        p.mb-0 De esta manera, la investigación participativa se plantea como un ejercicio transformador que trasciende lo académico. Su finalidad es empoderar a las comunidades campesinas, visibilizar sus problemáticas y fortalecer su capacidad de decisión sobre el uso del territorio y los recursos. Con ello, se construyen bases sólidas para alcanzar un desarrollo rural sostenible y equitativo.
</template>

<script>
export default {
  name: 'Introduccion',
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
