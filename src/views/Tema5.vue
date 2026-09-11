<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 #[em Marketing] y estrategias de crecimiento 

    img(data-aos="fade-up")(src="@/assets/curso/tema5/1.png", alt="")
    .row.justify-content-center.z-2
      .col-lg-10.p-4(data-aos="fade-down")
        div.banner-text.shadow
          p.mb-0 El #[em marketing] y las estrategias de crecimiento permiten a las organizaciones identificar oportunidades de mercado, fortalecer la relación con los clientes y desarrollar acciones orientadas al logro de los objetivos empresariales. Su aplicación facilita la generación de valor, el posicionamiento de la marca y el incremento de la competitividad en entornos cada vez más dinámicos y exigentes. 

    separador
    
    #t_5_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 5.1	#[em Marketing] estratégico y #[em marketing] operativo 

    p.mb-4 El #[em marketing] se desarrolla mediante actividades orientadas a comprender las necesidades de los consumidores y ofrecer soluciones que generen valor. Dentro de este proceso, el #[em marketing] estratégico y el #[em marketing] operativo cumplen funciones complementarias para la formulación y ejecución de las estrategias empresariales. 
    
    TabsB.color-secundario.z-2
      .py-4.py-md-5.px-4(titulo="<em>Marketing</em> estratégico" :icono="require_src('@/assets/curso/tema5/2.png')")
        .row.align-items-center.justify-content-center
          .col-sm-6.col-lg-3
            figure
              img.mb-4.mb-lg-0(src='@/assets/curso/tema5/5.png', alt='')
          .col-lg-9
            p El #[em marketing] estratégico se enfoca en el análisis del mercado, la identificación de oportunidades y la definición de acciones de largo plazo que permitan alcanzar ventajas competitivas. Su propósito consiste en establecer el rumbo comercial de la organización mediante la comprensión de las necesidades del cliente y las condiciones del entorno. 
            p Este enfoque implica actividades relacionadas con la segmentación de mercados, el análisis de la competencia, la identificación de oportunidades y la definición de objetivos estratégicos. La información obtenida permite tomar decisiones orientadas al crecimiento y sostenibilidad empresarial. 
            p.mb-0 Por ejemplo, una empresa puede identificar un segmento de consumidores interesados en productos ecológicos y diseñar una estrategia orientada a atender dicho mercado mediante una propuesta de valor diferenciada. 
      
      .py-4.py-md-5.px-4(titulo="<em>Marketing</em> operativo" :icono="require_src('@/assets/curso/tema5/3.png')")
        .row.align-items-center.justify-content-center
          .col-sm-6.col-lg-3
            figure
              img.mb-4.mb-lg-0(src='@/assets/curso/tema5/6.png', alt='')
          .col-lg-9
            p El #[em marketing] operativo corresponde a la ejecución de las acciones definidas en la estrategia comercial. Su enfoque es de corto y mediano plazo y busca implementar actividades que permitan alcanzar los objetivos establecidos por la organización. 
            p Entre las actividades del marketing operativo se encuentran la promoción, la gestión de canales de distribución, la publicidad, las ventas y la atención al cliente. Estas acciones permiten materializar las estrategias y generar resultados concretos dentro del mercado. 
            p.mb-0 Por ejemplo, una empresa que ha identificado una oportunidad en el mercado juvenil puede desarrollar campañas publicitarias específicas y promociones orientadas a dicho segmento para incrementar sus ventas. 

      .py-4.py-md-5.px-4(titulo="Relación entre marketing estratégico y marketing operativo" :icono="require_src('@/assets/curso/tema5/4.png')")
        .row.align-items-center.justify-content-center
          .col-sm-6.col-lg-3
            figure
              img.mb-4.mb-lg-0(src='@/assets/curso/tema5/7.png', alt='')
          .col-lg-9
            p El #[em marketing] estratégico define qué hacer y hacia dónde dirigir los esfuerzos organizacionales, mientras que el #[em marketing] operativo establece cómo ejecutar las acciones necesarias para alcanzar los objetivos propuestos. Ambos enfoques son complementarios y contribuyen al éxito de la gestión comercial y de mercadeo. 

    separador
    
    #t_5_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 5.2	#[em Marketing mix]

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-sm-6.col-lg-3
        figure
          img.mb-4.mb-lg-0(src="@/assets/curso/tema5/8.png", alt="" data-aos="zoom-in-down")
      .col-lg-9
        p El marketing mix es una herramienta utilizada para diseñar estrategias comerciales mediante la combinación de variables que influyen en la decisión de compra de los consumidores. Su aplicación permite estructurar acciones orientadas a satisfacer las necesidades del mercado y fortalecer la competitividad empresarial.
        .bg-terciario-t5.p-4.rounded-4.mb-4.mb-lg-0.py-3
          p.mb-0 Tradicionalmente, el marketing mix se encuentra conformado por cuatro variables fundamentales conocidas como las cuatro P: producto, precio, plaza y promoción. Estas variables deben gestionarse de manera integrada para alcanzar los objetivos comerciales de la organización.

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-lg-9
        AcordionA(tipo="b" clase-tarjeta="tarjeta bg-primario")
          div(titulo="Producto")
            .me-lg-5
              p.mb-0 El producto corresponde al bien o servicio ofrecido por la empresa para satisfacer necesidades o deseos de los consumidores. Incluye aspectos relacionados con calidad, diseño, características, empaque, marca y beneficios percibidos. 
          div(titulo="Precio")
            .me-lg-5
              p.mb-0 El precio representa el valor económico que el cliente debe pagar para adquirir un producto o servicio. Su definición debe considerar factores como costos, competencia, demanda y percepción de valor por parte de los consumidores. ambiente. 
          div(titulo="Plaza (distribución)")
            .me-lg-5
              p.mb-0 La plaza hace referencia a los canales de distribución utilizados para poner los productos o servicios a disposición de los consumidores. Incluye aspectos relacionados con logística, almacenamiento, transporte y puntos de venta. 
          div(titulo="Promoción")
            .me-lg-5
              p.mb-0 La promoción comprende las actividades de comunicación orientadas a informar, persuadir y recordar a los consumidores los beneficios de un producto o servicio. Incluye herramientas como publicidad, relaciones públicas, promoción de ventas, mercadeo digital y ventas personales. 
      .col-sm-6.col-lg-3.d-none.d-lg-block
        figure
          img.mb-4.mb-lg-0(src="@/assets/curso/tema5/9.png", alt="" data-aos="zoom-in-down")

    .row.justify-content-center.align-items-center
      .col-xl-10
        .tarjeta.bg-img.bg-img--primario.p-4
          .row.justify-content-around.align-items-center
            .col-3.col-lg-2.d-none.d-lg-block
              img.imgw-140(src="@/assets/curso/tema1/19.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5.mb-1 #[em MARKETING MI]X - Las 4p del #[em Marketing] - cómo aplicarlas y ejemplos 
                  p.mb-0 Para fortalecer los conocimientos sobre el marketing mix y comprender la aplicación de sus cuatro variables: producto, precio, plaza y promoción, se recomienda consultar el siguiente video, en el cual se explica cómo aplicar estas variables en la planificación de estrategias comerciales y se presentan ejemplos prácticos. 
                .col-sm-auto.d-flex.gap-2.flex-column
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=KiqUOstzOsk" target="_blank")
                    span Ir al recurso

    separador

    #t_5_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 5.3	Estrategias de mercado y crecimiento empresarial

    p.mb-4 Las estrategias de mercado permiten a las organizaciones fortalecer su posición competitiva y aprovechar oportunidades de crecimiento. Su aplicación facilita la expansión empresarial y contribuye al cumplimiento de los objetivos comerciales y financieros. 

    .p-4.bg-slider.rounded-4.mb-5
      .tarjeta.tarjeta--blanca
        SlyderA(tipo="a")
          div.mt-4.mb-5.w-75.mx-auto
            .row.justify-content-center.align-items-center
              .col-6.col-sm-4.col-lg-2
                img.mb-4.mb-lg-0.imgw-150(src="@/assets/curso/tema5/10.png", alt="")
              .col-lg-10
                h5 Estrategias del líder del mercado 
                p Las organizaciones líderes buscan mantener su posición competitiva mediante acciones orientadas a fortalecer la fidelización de clientes, innovar constantemente y ampliar su participación dentro del mercado. 
                p.mb-0 Estas empresas suelen realizar inversiones significativas en investigación, desarrollo y mercadeo para conservar su liderazgo y responder a las acciones de la competencia. 
          div.mt-4.mb-5.w-75.mx-auto
            .row.justify-content-center.align-items-center
              .col-6.col-sm-4.col-lg-2
                img.mb-4.mb-lg-0.imgw-150(src="@/assets/curso/tema5/11.png", alt="")
              .col-lg-10
                h5 Estrategias del retador
                p Las empresas retadoras buscan incrementar su participación de mercado mediante acciones dirigidas a competir con organizaciones líderes. Estas estrategias suelen enfocarse en la innovación, la diferenciación y la identificación de oportunidades poco atendidas por los competidores. 
                p.mb-0 El propósito es atraer clientes mediante propuestas de valor que resulten más atractivas o convenientes para determinados segmentos del mercado. 
          div.mt-4.mb-5.w-75.mx-auto
            .row.justify-content-center.align-items-center
              .col-6.col-sm-4.col-lg-2
                img.mb-4.mb-lg-0.imgw-150(src="@/assets/curso/tema5/12.png", alt="")
              .col-lg-10
                h5 Estrategias de especialización en nicho 
                p La especialización en nicho consiste en concentrar los esfuerzos comerciales en segmentos específicos del mercado con necesidades particulares. Esta estrategia permite desarrollar ofertas altamente especializadas y fortalecer la relación con grupos de clientes definidos. 
                p.mb-0 Las organizaciones que aplican esta estrategia suelen obtener ventajas derivadas del conocimiento profundo de las necesidades de su mercado objetivo. 
          div.mt-4.mb-5.w-75.mx-auto
            .row.justify-content-center.align-items-center
              .col-6.col-sm-4.col-lg-2
                img.mb-4.mb-lg-0.imgw-150(src="@/assets/curso/tema5/13.png", alt="")
              .col-lg-10
                h5 Penetración de mercado 
                p La penetración de mercado busca incrementar las ventas de productos o servicios existentes dentro de mercados ya atendidos por la organización. Para lograrlo, pueden implementarse acciones relacionadas con promociones, fortalecimiento de la comunicación comercial y mejora de la experiencia del cliente. 
                p.mb-0 Esta estrategia permite aumentar la participación de mercado sin necesidad de desarrollar nuevos productos. 
          div.mt-4.mb-5.w-75.mx-auto
            .row.justify-content-center.align-items-center
              .col-6.col-sm-4.col-lg-2
                img.mb-4.mb-lg-0.imgw-150(src="@/assets/curso/tema5/14.png", alt="")
              .col-lg-10
                h5 Desarrollo de nuevos productos 
                p El desarrollo de nuevos productos consiste en diseñar y comercializar bienes o servicios innovadores que permitan responder a necesidades emergentes o ampliar la oferta empresarial. Esta estrategia favorece la diversificación y el crecimiento organizacional. 
                p.mb-0 La innovación permanente contribuye a mantener la competitividad y fortalecer la propuesta de valor frente a los consumidores. 
          div.mt-4.mb-5.w-75.mx-auto
            .row.justify-content-center.align-items-center
              .col-6.col-sm-4.col-lg-2
                img.mb-4.mb-lg-0.imgw-150(src="@/assets/curso/tema5/15.png", alt="")
              .col-lg-10
                h5 Desarrollo de nuevos mercados 
                p El desarrollo de nuevos mercados implica la búsqueda de segmentos o territorios distintos de los actualmente atendidos por la organización. Esta estrategia permite ampliar la cobertura comercial y generar nuevas oportunidades de negocio. 
                p.mb-0 Las empresas pueden aplicar esta estrategia mediante la expansión geográfica, la atención de nuevos segmentos de clientes o la adaptación de productos y servicios a diferentes contextos de mercado. 
          div.mt-4.mb-5.w-75.mx-auto
            .row.justify-content-center.align-items-center
              .col-6.col-sm-4.col-lg-2
                img.mb-4.mb-lg-0.imgw-150(src="@/assets/curso/tema5/16.png", alt="")
              .col-lg-10
                h5 Importancia de las estrategias de crecimiento 
                p Las estrategias de crecimiento permiten a las organizaciones fortalecer su competitividad, incrementar sus ingresos y mejorar su capacidad de adaptación frente a los cambios del entorno. Su adecuada selección depende del análisis del mercado, las capacidades empresariales y los objetivos estratégicos definidos por la organización. 
                p.mb-0 La combinación de estrategias de #[em marketing] y crecimiento facilita el aprovechamiento de oportunidades comerciales y contribuye a la sostenibilidad empresarial en el largo plazo. 
 

</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
