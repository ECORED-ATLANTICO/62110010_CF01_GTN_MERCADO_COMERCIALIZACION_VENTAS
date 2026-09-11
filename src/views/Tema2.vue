<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Propuesta de valor y ventaja competitiva 

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require_src('@/assets/curso/tema6/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La propuesta de valor y la ventaja competitiva constituyen elementos fundamentales dentro de la planeación comercial y de mercadeo. Su análisis permite identificar las necesidades de los clientes, comprender los factores que influyen en las decisiones de compra y diseñar ofertas diferenciadas que generen valor para el mercado objetivo. Estas herramientas contribuyen al fortalecimiento del modelo de negocio y al posicionamiento de la organización frente a la competencia. 

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
