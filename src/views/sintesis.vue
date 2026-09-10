<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-sm-6.col-lg-3
        figure
          img.mb-4.mb-lg-0(src="@/assets/curso/sintesis.png", alt="" data-aos="zoom-in-down")
      .col-lg-9
        p El componente formativo Planeación comercial y de mercadeo con Canvas aborda el estudio del modelo de negocio Canvas, la propuesta de valor y la ventaja competitiva como elementos fundamentales para la formulación de estrategias empresariales. Asimismo, desarrolla herramientas de análisis estratégico y oportunidades de mercado mediante el análisis interno y externo de la organización.
        .bg-img.bg-img--contenido.p-4.rounded-4.overflow-hidden
          p.mb-0 De igual manera, estudia la segmentación y el posicionamiento de mercado, así como el marketing y las estrategias de crecimiento empresarial orientadas al fortalecimiento de la competitividad. Finalmente, integra estrategias comerciales y de mercadeo que contribuyen a la formulación de planes comerciales y de mercadeo alineados con los objetivos organizacionales y las necesidades del mercado.

    .row.justify-content-center
      .col-lg-12
        figure
          img.mb-5(src="@/assets/curso/sintesis.svg", alt="")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
