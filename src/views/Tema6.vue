<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Estrategias comerciales y de mercadeo

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require_src('@/assets/curso/tema6/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las estrategias comerciales y de mercadeo permiten a las organizaciones fortalecer su relación con los clientes, incrementar la visibilidad de sus productos o servicios y mejorar su posición competitiva dentro del mercado. Su aplicación facilita la generación de experiencias de valor, el fortalecimiento de la marca y el cumplimiento de los objetivos comerciales mediante acciones orientadas a satisfacer las necesidades y expectativas de los consumidores. 
    
    separador
    #t_6_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 6.1	#[em Marketing] experiencial, mercadotecnia directa y #[em neuromarketing]

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.z-2
      .col-lg-9
        p Las organizaciones actuales buscan establecer relaciones más cercanas con sus clientes mediante estrategias que permitan comprender mejor sus comportamientos, emociones y necesidades. En este contexto, el #[em marketing] experiencial, la mercadotecnia directa y el #[em neuromarketing] se han convertido en herramientas relevantes para fortalecer la comunicación comercial y generar valor.
        .bg-botones-a5.p-4.rounded-4.mb-4.py-3
          p.mb-0 Estas estrategias presentan diferentes formas de relacionarse con el consumidor, desde la creación de experiencias hasta la comunicación personalizada y el análisis de los factores que influyen en sus decisiones de compra. 
      .col-sm-6.col-lg-3
        figure
          img(data-aos="fade-down-right", src="@/assets/curso/tema6/2.png", alt="")
    
    .row.justify-content-center.align-items-center.z-2.mb-4
      .col-sm-6.col-lg-3.d-none.d-xl-block
        figure
          img(data-aos="fade-down-right", src="@/assets/curso/tema6/3.png", alt="")
      .col-xl-9
        TabsA.color-secundario.custom-tabs
          .tarjeta.p-4.bg-contenido-a5.py-5(titulo="<em>Marketing</em> experiencial")
            p El marketing experiencial consiste en diseñar experiencias memorables que permitan al cliente interactuar de manera significativa con una marca, producto o servicio. Busca generar emociones positivas que fortalezcan la relación con el consumidor y aumenten la probabilidad de recompra. 
            p Esta estrategia reconoce que los clientes no solo adquieren productos o servicios, sino también experiencias que influyen en su percepción y satisfacción. Por ello, las organizaciones desarrollan actividades que estimulan los sentidos, las emociones y la participación del consumidor. 
            p.mb-0 #[strong Ejemplo:] una tienda de artículos deportivos organiza eventos donde los clientes prueban productos, participan en actividades recreativas y comparten experiencias con otros usuarios. 
          .tarjeta.p-4.bg-contenido-a5.py-5(titulo="Mercadotecnia directa")
            p La mercadotecnia directa busca establecer contacto con clientes actuales o potenciales para promover productos, servicios o campañas comerciales. Permite personalizar los mensajes y medir con mayor precisión los resultados obtenidos. 
            p Entre los medios utilizados se encuentran el correo electrónico, las llamadas telefónicas, los mensajes de texto, las redes sociales y las plataformas digitales. Una adecuada implementación contribuye a mejorar la efectividad de las campañas y optimizar los recursos destinados a la promoción. 
            p.mb-0 #[strong Ejemplo:] una empresa envía mensajes personalizados a sus clientes para comunicar una promoción relacionada con sus intereses de compra.  
          .tarjeta.p-4.bg-contenido-a5.py-5(titulo="<em>Neuromarketing</em>")
            p El neuromarketing estudia la influencia de los estímulos comerciales sobre el comportamiento del consumidor mediante el análisis de procesos mentales y emocionales relacionados con la toma de decisiones. 
            p Su aplicación permite comprender cómo colores, sonidos, imágenes, aromas y mensajes publicitarios pueden influir en las preferencias y decisiones de compra. Esta información facilita el diseño de estrategias comerciales más efectivas y orientadas a las expectativas del mercado. 
            p.mb-0 #[strong Ejemplo:] una marca analiza la respuesta de los consumidores ante diferentes elementos visuales de un anuncio para mejorar su comunicación comercial. 

    .row.justify-content-center.align-items-center
      .col-xl-10
        .tarjeta.bg-img.bg-img--terciario.p-4
          .row.justify-content-around.align-items-center
            .col-3.col-lg-2.d-none.d-lg-block
              img.imgw-120(src="@/assets/curso/tema1/15.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Estrategias de mercado: ¿Qué son y cuáles son sus tipos? ¡Descubre este concepto y ejemplos de cómo hacerlas! 
                  p.mb-0 Para ampliar los conocimientos sobre las estrategias de mercado y comprender su importancia en el logro de los objetivos comerciales, se recomienda consultar el siguiente artículo, en el cual se explican su concepto, importancia, tipos y pasos para su elaboración, acompañados de ejemplos prácticos. 
                .col-sm-auto.d-flex.gap-2.flex-column
                  a.boton.color-acento-botones(href="https://escala.com/estrategias-de-mercado/" target="_blank")
                    span Ir al recurso

    separador
    #t_6_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 6.2	#[em Merchandising, store planning] y #[em layout]

    .bg-primario-p5.mb-4.mb-lg-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto
          figure
            img(src='@/assets/curso/tema6/4.png', alt='')
        .col-lg
          .p-4
            p.mb-0 Las estrategias relacionadas con la organización de los espacios comerciales buscan mejorar la experiencia de compra y aumentar la visibilidad de los productos dentro del punto de venta. Estas herramientas permiten optimizar la presentación comercial y facilitar la interacción entre los consumidores y la oferta empresarial. 

    p.mb-4.mb-lg-5 Para comprender cómo estas estrategias contribuyen a la organización y presentación del espacio comercial, se presentan a continuación sus principales características y aplicaciones. 

    .p-4.bg-slider.rounded-4.mb-5
      .tarjeta.tarjeta--blanca
        SlyderA(tipo="a")
          div.mt-4.mb-5.w-75.mx-auto
            .row.justify-content-center.align-items-center
              .col-lg-10
                h5 #[em Merchandising]
                p Comprende técnicas aplicadas en el punto de venta para presentar la oferta de manera atractiva, estimular la compra y facilitar la decisión del consumidor. Incluye la organización y exhibición estratégica de productos, la ambientación y el uso de elementos promocionales. 
                p.mb-4.mb-lg-0 #[strong Ejemplo:] organizar los productos y elementos promocionales de una tienda para aumentar su visibilidad y facilitar la compra. 
              .col-6.col-sm-4.col-lg-2
                img.imgw-150(src="@/assets/curso/tema6/5.png", alt="")
          div.mt-4.mb-5.w-75.mx-auto
            .row.justify-content-center.align-items-center
              .col-lg-10
                h5 #[em Store planning]
                p Es el proceso de planificación y organización de los espacios comerciales para optimizar la circulación de los clientes y mejorar la exhibición de los productos. Considera la distribución de áreas, ubicación de secciones, recorridos y aprovechamiento del espacio. 
                p.mb-4.mb-lg-0 #[strong Ejemplo:] distribuir las secciones de una tienda para facilitar el recorrido de los clientes. 
              .col-6.col-sm-4.col-lg-2
                img.imgw-150(src="@/assets/curso/tema6/6.png", alt="")
          div.mt-4.mb-5.w-75.mx-auto
            .row.justify-content-center.align-items-center
              .col-lg-10
                h5 #[em Layout]
                p Hace referencia a la distribución física de los elementos dentro de un espacio comercial, como productos, mobiliario, pasillos y cajas de pago. Su diseño permite mejorar la circulación, aumentar la visibilidad de los productos y aprovechar el espacio. 
                p.mb-4.mb-lg-0 #[strong Ejemplo:] ubicar estratégicamente productos, pasillos y cajas para facilitar la circulación y la atención. 
              .col-6.col-sm-4.col-lg-2
                img.imgw-150(src="@/assets/curso/tema6/7.png", alt="")

    .row.justify-content-center.align-items-center
      .col-xl-10
        .tarjeta.bg-img.bg-img--primario.p-4
          .row.justify-content-around.align-items-center
            .col-3.col-lg-2.d-none.d-lg-block
              img.imgw-140(src="@/assets/curso/tema1/19.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5.mb-1 #[em NEUROMARKETING:] Qué es y TÉCNICAS que se utilizan 
                  p.mb-0 Para complementar los conocimientos sobre el neuromarketing y comprender su aplicación en las estrategias comerciales, se recomienda consultar el siguiente video, en el cual se explica su concepto y se presentan algunas de las técnicas utilizadas para analizar la respuesta del consumidor ante diferentes estímulos. 
                .col-sm-auto.d-flex.gap-2.flex-column
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=L_nbK-G9s_4" target="_blank")
                    span Ir al recurso

    separador
    #t_6_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 6.3	Señalética, escaparatismo e iluminación

    p.mb-4.mb-lg-5 La comunicación visual desempeña un papel fundamental dentro de los espacios comerciales, ya que facilita la orientación de los clientes, mejora la presentación de los productos y fortalece la imagen corporativa. La señalética, el escaparatismo y la iluminación constituyen herramientas ampliamente utilizadas para este propósito. 

    .row.justify-content-center.mb-5
      .col-sm-11.col-lg-8.col-xl-6.mb-4
        .crd_hover_txt(data-aos="flip-left").tarjeta
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/tema6/8.png", alt="alt")
          .crd_hover_txt--body.pt-4
            h4.mb-2.mb-lg-3 Señalética 
            p.mb-2 La señalética corresponde al conjunto de elementos visuales utilizados para orientar, informar y guiar a los clientes dentro de un establecimiento comercial. Su adecuada implementación facilita la ubicación de productos, servicios y áreas específicas del negocio. 
            p.mb-0 Entre los elementos más utilizados se encuentran avisos informativos, indicadores de dirección, señales de seguridad y material gráfico de apoyo. Una señalética clara contribuye a mejorar la experiencia del consumidor y optimizar la circulación dentro del punto de venta. 
    
      .col-sm-11.col-lg-8.col-xl-6.mb-4
        .crd_hover_txt(data-aos="flip-left").tarjeta
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/tema6/9.png", alt="alt")
          .crd_hover_txt--body.pt-4
            h4.mb-2.mb-lg-3 Escaparatismo 
            p.mb-2 El escaparatismo consiste en el diseño y organización de vitrinas con el propósito de atraer la atención de los consumidores y comunicar mensajes comerciales de manera visual. Esta técnica busca destacar productos, fortalecer la imagen de marca e incentivar el ingreso de clientes al establecimiento. 
            p.mb-2 La construcción de escaparates requiere la integración de elementos como color, iluminación, composición visual y temáticas promocionales que permitan generar impacto y despertar interés en el público objetivo. 
            p.mb-0 Una vitrina bien diseñada puede convertirse en una herramienta efectiva para incrementar la visibilidad de la oferta comercial y estimular las ventas. 
    
      .col-sm-11.col-lg-8.col-xl-6.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left").tarjeta
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/tema6/10.png", alt="alt")
          .crd_hover_txt--body.pt-4
            h4.mb-2.mb-lg-3 Iluminación 
            p.mb-2 La iluminación es un recurso estratégico que contribuye a resaltar productos, mejorar la ambientación del establecimiento y fortalecer la percepción de calidad por parte de los clientes. Su adecuada utilización permite crear entornos más atractivos y funcionales. 
            p.mb-2 Las organizaciones emplean diferentes tipos de iluminación según los objetivos comerciales y las características de los espacios. Entre ellas se encuentran la iluminación general, decorativa y de acento, cada una orientada a generar efectos visuales específicos. 
            p.mb-0 La combinación adecuada de iluminación, señalética y escaparatismo contribuye a fortalecer la comunicación visual y mejorar la experiencia de compra dentro de los espacios comerciales. 
 
      .col-sm-11.col-lg-8.col-xl-6.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left").tarjeta
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/tema6/11.png", alt="alt")
          .crd_hover_txt--body.pt-4
            h4.mb-2.mb-lg-3 Importancia de las estrategias comerciales y de mercadeo 
            p.mb-2 Las estrategias comerciales y de mercadeo permiten fortalecer la relación con los clientes, mejorar la experiencia de compra y aumentar la competitividad empresarial. Su adecuada implementación favorece el posicionamiento de la marca, el incremento de las ventas y el logro de los objetivos organizacionales. 
            p.mb-0 La integración de herramientas relacionadas con la experiencia del cliente, la comunicación comercial y la organización de espacios comerciales contribuye a generar valor y a construir relaciones duraderas con los consumidores en mercados cada vez más dinámicos y competitivos. 

</template>

<script>
export default {
  name: 'Tema6',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
