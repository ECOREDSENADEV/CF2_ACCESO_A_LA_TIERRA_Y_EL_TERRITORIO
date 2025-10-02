<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Métodos de investigación básica en comunidades campesinas
    
    .row.mb-5.align-items-center
      .col-lg-4.mb-3.mb-lg-0.order-2
        figure
          img(src="@/assets/curso/tema2/1.png", data-aos="zoom-in")
      .col-lg-8.order-1
        p(data-aos="fade-left") La investigación básica, se refiere a conocer y aplicar metodologías de investigación que permiten observar y recolectar información sobre aspectos clave que afectan el bienestar y el desarrollo futuro de las comunidades campesinas, como el acceso a servicios básicos, el nivel de organización comunitaria y las prácticas agropecuarias sostenibles.
    
        .row.align-items-start.mb-3
          .col-lg-auto.order-2
            img(src="@/assets/curso/tema2/2.svg", style="max-width: 190px").mx-auto
          .col-lg.order-1.mb-3.mb-lg-0
            div.bg-color-4.px-5.py-4.tarjeta
              p.mb-0 Para ello, se utilizan distintos instrumentos de recolección de información que permiten obtener datos cercanos a la realidad. Estos datos se analizan con el fin de sacar conclusiones y proponer posibles soluciones, siempre involucrando a la comunidad en todo el proceso.
        
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema1/3.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Este tipo de investigación se basa en la sencillez y claridad en cada una de sus etapas, lo cual garantiza que todos los integrantes de la comunidad comprendan el proceso. El objetivo principal es obtener una radiografía del estado actual de la comunidad, sus potencialidades y las alternativas de solución a sus problemáticas.

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
