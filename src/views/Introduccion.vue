<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .bg-primario-p5.mb-4.mb-lg-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg
          .p-4
            p.mb-0 El componente formativo Planeación comercial y de mercadeo con Canvas aborda el estudio de herramientas y estrategias orientadas al diseño de modelos de negocio, la generación de propuestas de valor y la formulación de planes comerciales y de mercadeo como elementos fundamentales para la competitividad empresarial. 
        .col-lg-auto
          figure
            img(src='@/assets/curso/intro.png', alt='')

    p.mb-4 En este contexto, el modelo de negocio Canvas facilita la comprensión de los factores que intervienen en la creación, entrega y captura de valor, permitiendo estructurar iniciativas comerciales alineadas con las necesidades del mercado y los objetivos organizacionales.

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-sm-8.col-lg-4
        figure
          img.mb-4.mb-lg-0(src="@/assets/curso/intro-2.png", alt="" data-aos="zoom-in-down")
      .col-lg-8
        p A través del desarrollo de este componente se analizan conceptos relacionados con el modelo de negocio Canvas, la propuesta de valor, la ventaja competitiva, el análisis estratégico, la segmentación de mercados, el posicionamiento y las estrategias de crecimiento empresarial. Asimismo, se estudian herramientas como el mapa de empatía, la curva de valor, la matriz DOFA, el análisis PEST y el Benchmark, las cuales contribuyen a identificar oportunidades de mercado y apoyar la toma de decisiones comerciales.
        .bg-img.bg-img--contenido.p-4.rounded-4.overflow-hidden
          p.mb-0 De igual manera, el componente integra fundamentos de mercadeo estratégico y operativo, estrategias comerciales y herramientas orientadas al fortalecimiento de la relación con los clientes y la generación de valor empresarial. A lo largo del desarrollo temático se abordarán conceptos, metodologías y aplicaciones prácticas que fortalecerán la formulación de planes comerciales y de mercadeo, favoreciendo el crecimiento, el posicionamiento y la competitividad de las organizaciones.



</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
