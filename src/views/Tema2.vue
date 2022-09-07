<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1  Vulnerabilidades en aplicaciones web

    .row.justify-content-center.align-items-center.mb-4
      .col-md-10
        .bloque-texto-g.color-acento-botones.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img1.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Actualmente se cuenta con una amplia gama de recursos normativos y estándares para la gestión de vulnerabilidades, algunas de ellas con un nivel de cobertura más amplio dado su capacidad de aplicación dentro de las necesidades de una organización. Cada una de estas normas tiene como talante la gestión proactiva de las vulnerabilidades antes de una ocurrencia de un incidente que ponga en riesgo la información administrada
    separador
    
    #t_2_1.titulo-segundo.color-acento-contenido
      .h4 2.1 Infografía Animada

    p.mb-4 Owasp propone una metodología para la identificación de vulnerabilidades basada en pruebas de seguridad sobre las aplicaciones web, con el cual se busca encontrar las debilidades presentes en un sistema.
    p.mb-4 Este modelo de pruebas está conformado por:

    .row.mb-4
      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.rounded-0.bg--a-1.p-4.d-flex.flex-column.h-100.hoverScale2
          img.mb-2(src='@/assets/curso/tema2/1.png' style='width: 40px').mx-auto
          .row.justify-content-center.align-items-center.mb-2
            .col-md-8
              .tarjeta.color-primario.p-3
                h4.text-center.text-white.mb-0 Probador/Auditor: 
          p.text-center Quien realiza las pruebas y validaciones.
      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.rounded-0.bg--a-1.p-4.d-flex.flex-column.h-100.hoverScale2
          img.mb-2(src='@/assets/curso/tema2/2.png' style='width: 40px').mx-auto
          .row.justify-content-center.align-items-center.mb-2
            .col-md-10
              .tarjeta.color-primario.p-3
                h4.text-center.text-white.mb-0 Herramientas y metodología:  
          p.text-center Guía de pruebas de Owasp.
      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.rounded-0.bg--a-1.p-4.d-flex.flex-column.h-100.hoverScale2
          img.mb-2(src='@/assets/curso/tema2/3.png' style='width: 40px').mx-auto
          .row.justify-content-center.align-items-center.mb-2
            .col-md-6
              .tarjeta.color-primario.p-3
                h4.text-center.text-white.mb-0 Aplicación: 
          p.text-center Objeto que se desea probar.
    
    P.mb-4 A su vez, las pruebas se pueden clasificar así:

    .tarjeta.tarjeta-color.p-5.mb-5
      SlyderA(tipo="b")
        .row
          .col-md-6.mb-4.mb-md-0
            h5 Pruebas pasivas 
            p El probador intenta comprender la lógica de la aplicación y explora la aplicación web como un usuario. Se pueden utilizar herramientas para la recopilación de información. Por ejemplo, se puede utilizar un proxy HTTP para observar todas las solicitudes y respuestas. Al final de esta fase, el probador generalmente debe comprender todos los puntos de acceso y la funcionalidad del sistema (por ejemplo, encabezados HTTP, parámetros, cookies, API, uso / patrones de tecnología, etc.).
          .col-md-6
            figure
              img(src='@/assets/curso/tema2/img2.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h5 Pruebas activas
            p Durante estas pruebas, un probador comienza a utilizar las metodologías descritas en las siguientes secciones, las cuales están divididas en 12 categorías:
            p.mb-0 01. Recopilación de información.
            p.mb-0 2 Pruebas de administración de configuración e implementación.
            p.mb-0 03. Pruebas de administración de identidades.
            p.mb-0 04. Pruebas de autenticación.
            p.mb-0 05. Pruebas de autorización.
            p.mb-0 06. Pruebas de gestión de sesiones.
            p.mb-0  07. Pruebas de validación de entrada.
            p.mb-0 08. Manejo de errores.
            p.mb-0  09. Criptografía.
            p.mb-0  10. Pruebas de lógica empresarial.
            p.mb-0  11. Pruebas del lado del cliente.
            p.mb-0 12. Pruebas de API.
          .col-md-6
            figure
              img(src='@/assets/curso/tema2/img3.png', alt='Texto que describa la imagen')
    separador
   
    #t_2_2.titulo-segundo.color-acento-contenido
      .h4 2.2 Video Motion

    p.mb-4 Dentro del ejercicio de la gestión de vulnerabilidades, cobran vital importancia las metodologías para el descubrimiento e identificación de estas, ya que orientan y dan un mapa de ruta de cómo se debe realizar el ejercicio, uno de estos es el pentesting o prueba de penetración, que no es más que un ejercicio de descubrimiento apoyado en técnicas y herramientas especializadas para la validación y búsqueda de vulnerabilidades en un sistema o aplicación.
    p.mb-4 Existen los siguientes tipos de pentesting:

    .row 
      .col-md-12
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta-azul")
          .row(titulo="Prueba en aplicación web")
            .col-md-9.mb-4.mb-md-0
              p Es una exploración profunda en una aplicación de tipo web, realizando análisis extremadamente detallados, para identificar vulnerabilidades que pueden poner en riesgo la información.

            .col-md-3
              figure
                img(src='@/assets/curso/tema2/4.png', alt='Texto que describa la imagen')

          .row(titulo="Prueba de Client Side")
            .col-md-9.mb-4.mb-md-0
              p En este tipo de prueba, es posible analizar software, programas de creación de contenido y Web browsers (como Chrome, Firefox, Explorer, etc) en ordenadores de los usuarios, para la búsqueda de vulnerabilidades.
          
            .col-md-3
              figure
                img(src='@/assets/curso/tema2/5.png', alt='Texto que describa la imagen')

          .row(titulo="Prueba en red inalámbrica")
            .col-md-9.mb-4.mb-md-0
              p Se examinan las redes inalámbricas validando protocolos, puntos de acceso y credenciales administrativas.
          
            .col-md-3
              figure
                img(src='@/assets/curso/tema2/6.png', alt='Texto que describa la imagen')

          .row(titulo="Prueba de Ingeniería Social")
            .col-md-9.mb-4.mb-md-0
              p Se analizan las informaciones y datos confidenciales que pueden ser objeto de robo por medio de manipulación psicológica, aprovechándose del ingenio o desconocimiento del usuario.  
          
            .col-md-3
              figure
                img(src='@/assets/curso/tema2/7.png', alt='Texto que describa la imagen')

    p.mb-4 Para cualquiera de los tipos de pentesting, se sugiere un ciclo de vida como se muestra en la siguiente figura, en donde se resalta:

    .row 
      .col-md-12
        TabsA.color-acento-contenido.mb-5
          .tarjeta.color-acento-contenido--borde.p-4(titulo="Reconocimiento:")
            .row
              .col-md-9
                h5 Reconocimiento: 
                p Identificar los activos de información, aplicaciones, dispositivos, información de red, credenciales de acceso, información.
              .col-md-3
                figure
                  img(src='@/assets/curso/tema2/img2.jpg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-contenido--borde.p-4(titulo="Fuera del hogar")
            .row
              .col-md-9
                h5 Análisis de vulnerabilidades:
                p.mb-4 Realizar mediante la aplicación de técnicas y herramientas especializadas, la búsqueda de posibles vulnerabilidades que pueden afectar un activo de información.
              .col-md-3
                figure
                  img(src='@/assets/curso/tema2/img2.jpg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-contenido--borde.p-4(titulo="Ropa tecnológica (wearables)")
            .row
              .col-md-9
                h5 Explotación:
                p Permite validar si una vulnerabilidad es explotable o puede permanecer en estado inactivo.
              .col-md-3
                figure
                  img(src='@/assets/curso/tema2/img2.jpg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-contenido--borde.p-4(titulo="Transporte")
            .row
              .col-md-9
                h5 Escalar privilegios o postexplotación:
                p Permite evaluar los posibles daños que pueden causar si una vulnerabilidad se materializa como amenaza.
              .col-md-3
                figure
                  img(src='@/assets/curso/tema2/img2.jpg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-contenido--borde.p-4(titulo="Contadores inteligentes")
            .row
              .col-md-9
                h5 Informe:
                p Generar el reporte del ejercicio realizado, hallazgos y detalles de las vulnerabilidades encontradas.
              .col-md-3
                figure
                  img(src='@/assets/curso/tema2/img2.jpg', alt='Texto que describa la imagen')
    
    P.mb-4 Ahora bien, este ejercicio se puede realizar de manera exploratoria sin conocimiento del escenario e información de acceso, y dependiendo de esto, las pruebas se pueden clasificar en:


    #t_2_3.titulo-segundo.color-acento-contenido
      .h4 2.3 Motion + Presentador

    
    #t_2_4.titulo-segundo
      .h4 2.4 Animación 2D

   
    #t_2_5.titulo-segundo.color-acento-contenido
      .h4 2.5 Video interactivo

   
    #t_2_6.titulo-segundo.color-acento-contenido
      .h4 2.6 Infografías


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
