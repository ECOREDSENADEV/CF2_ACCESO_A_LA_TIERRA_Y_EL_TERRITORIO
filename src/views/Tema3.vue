<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Herramientas tecnológicas para sistematizar y/o tabular información
    
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/1.png')})`}"
      )(data-aos="zoom-in")
      .bloque-texto-g__texto.p-4
        p.mb-0 En la actualidad, con el avance acelerado de la tecnología, existen múltiples formas de clasificar, analizar y representar información. Para aprovechar estas herramientas es necesario contar con conocimientos básicos en el manejo del computador y algunos programas como Excel y Word. Si las personas no tienen formación previa en estos programas, es posible adquirir estas competencias a través de capacitaciones ofrecidas por instituciones como el SENA, alcaldías, colegios u organizaciones comunitarias.
    
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.svg")
        h3.titulo-con-imagen__texto Principales programas utilizados
      
    .row.mb-5.align-items-center
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/2.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
    
        .bg-color-18.tarjeta.p-5(data-aos="fade-left")
          p.mb-0 Entre los programas más comunes y accesibles que pueden emplearse para sistematizar o tabular información en una investigación participativa, se encuentran dos herramientas ampliamente conocidas y disponibles en la mayoría de equipos: <b>Microsoft Word y Microsoft Excel</b>. A continuación, se describen sus funciones y aplicaciones más relevantes.
    
    TabsB.color-acento-contenido.mb-5
      .py-4.py-md-5(titulo="Microsoft Word" :icono="require('@/assets/componentes/9.svg')")
        .row.align-items-center.p-5
          .col-lg-7.mb-4.mb-md-0
            h4 Microsoft Word
            p <b>Word</b> es un programa de procesamiento de texto que permite <b>escribir, editar y dar formato a documentos</b>. En una investigación participativa, es especialmente útil para:
            ul.lista-ul--color
              li.mb-0.d-flex
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Redactar informes, descripciones, narraciones y reflexiones.
              li.mb-0.d-flex
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Presentar la parte cualitativa de la investigación.
              li.mb-0.d-flex
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Plasmar análisis, conclusiones y estrategias comunitarias para la solución de problemas.
          .col-lg-5.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/3.png', alt='Texto que describa la imagen')
      .py-4.py-md-5(titulo="Microsoft Excel" :icono="require('@/assets/componentes/10.svg')")
        .row.align-items-center.p-5
          .col-lg-7.mb-4.mb-md-0
            h4 Microsoft Excel
            p <b>Excel<</b> es un programa de hojas de cálculo diseñado para <b>organizar y analizar datos numéricos y categóricos</b>. Entre sus funciones principales se encuentran:
            ul.lista-ul--color
              li.mb-0.d-flex
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Crear tablas para registrar la información recolectada.
              li.mb-0.d-flex
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Realizar operaciones matemáticas básicas (suma, resta, multiplicación, división).
              li.mb-0.d-flex
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Calcular porcentajes y realizar agrupaciones de datos.
              li.mb-0.d-flex
                i.fas.fa-leaf.bg-color-7
                p.mb-0 Facilitar el análisis estadístico y la representación gráfica.
            p Este programa es especialmente útil para investigaciones realizadas en zonas veredales o territorios rurales, donde se requiere manejar datos sencillos pero significativos.
          .col-lg-5.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/4.png', alt='Texto que describa la imagen')
      

</template>

<script>
export default {
  name: 'Tema3',
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
