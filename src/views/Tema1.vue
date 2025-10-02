<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 ¿A qué nos referimos con hacer investigación dentro de una comunidad campesina?

    .row.mb-5.align-items-center
      .col-lg-4.mb-3.mb-lg-0.order-2
        figure
          img(src="@/assets/curso/tema1/1.png", data-aos="zoom-in")
      .col-lg-8.order-1
        p(data-aos="fade-left") Hacer investigación significa buscar respuestas a preguntas que tenemos sobre un tema, utilizando un método ordenado para observar, recolectar información, analizarla y llegar a conclusiones. En el contexto de una comunidad campesina, esta labor cobra un sentido práctico y social fundamental, ya que permite caracterizar a la comunidad, es decir, definir los rasgos que la distinguen de otras y comprender su realidad particular.
    
        .row.align-items-start.mb-3
          .col-lg-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/tema1/2.png", style="max-width: 190px").mx-auto
          .col-lg
            div.bg-color-5.px-5.py-4.tarjeta
              p.mb-0 Además, cuando se presenta una situación específica o un problema que necesita resolverse, la investigación nos permite realizar un diagnóstico. Esto implica evaluar la situación, analizar las causas y consecuencias, y plantear posibles soluciones. En este sentido, la investigación se convierte en una herramienta clave para la transformación social.
        
        .row.align-items-center
          .col-lg-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/tema1/3.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Dentro del programa es fundamental conocer a fondo las comunidades campesinas, identificar las problemáticas más relevantes que enfrentan y contribuir a la gestión de soluciones sostenibles. Por esta razón, es necesario aprender y aplicar métodos y herramientas de investigación adaptados a este contexto.
    
    p.mb-5 A continuación, se presentan los aspectos fundamentales que nos permitirán obtener una radiografía del nivel de bienestar en las comunidades campesinas:

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-color-white-1.p-4
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0.order-2
              figure
                img(src="@/assets/curso/tema1/4.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Prestación de servicios básicos
              p Nivel de acceso a servicios esenciales como agua potable, electricidad, salud, educación y saneamiento.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0.order-2
              figure
                img(src="@/assets/curso/tema1/5.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Capacidad de organización
              p Grado de articulación y participación de la comunidad en organizaciones campesinas, así como su incidencia en la toma de decisiones.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0.order-2
              figure
                img(src="@/assets/curso/tema1/6.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Prácticas agropecuarias sostenibles
              p Nivel de implementación de métodos agrícolas y ganaderos que respeten el medio ambiente, aseguren la productividad y garanticen la sostenibilidad a largo plazo.
          
    
    
 
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
