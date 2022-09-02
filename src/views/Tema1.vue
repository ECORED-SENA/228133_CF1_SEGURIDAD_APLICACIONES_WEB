<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Fundamentos de seguridad en aplicaciones web

    .row.justify-content-center.align-items-center.mb-4
      .col-md-9
        p.mb-4 La seguridad de la información en las organizaciones presenta una responsabilidad compartida dada por algunas normas, estándares, implementaciones de cumplimiento legal y algunas iniciativas de buenas prácticas que conllevan a generar una cultura de seguridad en los datos gestionados. 
        p.mb-4 Ahora bien, existe un gran número de este tipo de iniciativas enfocadas a la seguridad perimetral, de procesos, de infraestructura, y no se le da la correspondiente importancia al desarrollo de aplicaciones las cuales son la ventana o interfaz que los usuarios o clientes van a utilizar para acceder y gestionar la información.
        p.mb-4 De acuerdo con lo anterior, a continuación, se reconocerán algunas iniciativas que han surgido y que son muy utilizadas dentro de la seguridad de aplicaciones web.
      .col-md-3
        figure
          img(src='@/assets/curso/tema1/img1.png', alt='Mujer con tablet')
    separador

    #t_1_1.titulo-segundo.color-acento-contenido
      .h4 1.1 Conceptos

    p.mb-4 Dentro del ejercicio de la gestión de las vulnerabilidades en aplicaciones web se hará uso de metodologías, técnicas y herramientas especializadas, las cuales presentan términos que no son muy comunes y que es necesario reconocer para dar una adecuada interpretación de la información, así como transmitir los resultados obtenidos.
    p.mb-4 Se invita a conocer cuáles son los principales conceptos de vulnerabilidades en aplicaciones web:

    .row.justify-content-center.mb-5
      .col-lg-4.mb-4.mb-lg-0
        .crd.crd--grayGrad(data-aos="flip-left")
          .bottomCircle.mb-3
            figure
              img(src="@/assets/curso/tema1/icon1.png", alt="alt").img90.m-auto
          .row.justify-content-center.mb-5
            .col-md-6
              .tarjeta.clr--gris
                h4.text-center.p-2 Vulnerabilidad
          p.text-center.mb-0 Es una debilidad o fallo en un sistema de información que pone en riesgo la seguridad de la información.

      .col-lg-4.mb-4.mb-lg-0
        .crd.crd--grayGrad(data-aos="flip-left")
          .bottomCircle.mb-3
            figure
              img(src="@/assets/curso/tema1/icon2.png", alt="alt").img90.m-auto
          .row.justify-content-center.mb-5
            .col-md-6
              .tarjeta.clr--gris
                h4.text-center.p-2 Amenaza
          p.text-center.mb-0 Es toda acción que aprovecha una vulnerabilidad para atentar contra la seguridad de un sistema de información.


      .col-lg-4.mb-4.mb-lg-0
        .crd.crd--grayGrad(data-aos="flip-left")
          .bottomCircle.mb-3
            figure
              img(src="@/assets/curso/tema1/icon3.png", alt="alt").img90.m-auto
          .row.justify-content-center.mb-5
            .col-md-6
              .tarjeta.clr--gris
                h4.text-center.p-2 Riesgo
          p.text-center.mb-0 Es la probabilidad de que se produzca un incidente de seguridad, materializándose una amenaza y causando pérdidas o daños.
    
    .row.justify-content-center.align-items-center.mb-4
      .col-md-11
        .row.justify-content-center.align-items-center
          .col-md-8
            .cajon-b.color-acento-botones.p-3
              p.mb-0 Los anteriores conceptos deben ser comprendidos adecuadamente, pues la presencia de una vulnerabilidad no significa que esté afectando la información, como se observa en la siguiente figura, el riesgo resulta del aprovechamiento de una vulnerabilidad y una amenaza materializada 
              br
              br
              | En el siguiente recurso, se ofrece información en detalle de la relación de otros conceptos, se invita a consultarlo:
          .col-md-4
            figure
              img(src="@/assets/curso/tema1/img2.png", alt="alt")

    p.mb-4 A continuación, se podrán conocer otros conceptos importantes:

    .tarjeta.tarjeta-color.p-5.mb-5
      SlyderA(tipo="b")
        .row
          .col-md-6.mb-4.mb-md-0
            h5 Bug
            p Es una falla o error en un programa que puede generar problemas en el procesamiento de la información, debido a fallas en la programación o causado por compatibilidades entre sistemas.
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder1.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h5 Patch
            p También conocido como parche, es una pieza de programa adicional que corrige un bug o adiciona funcionalidades en una aplicación.	
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder2.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h5 Testing
            p También conocidas como pruebas, son un conjunto de técnicas y pruebas utilizadas dentro de la auditoría de aplicaciones web para verificar si estas son vulnerables o no ante dicha amenaza.         
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder3.png', alt='Texto que describa la imagen')
  
        .row
          .col-md-6.mb-4.mb-md-0
            h5 Medida
            p Corresponde a las mediciones realizadas en una prueba de auditoría, la cual es útil para tomar decisiones.         
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder4.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h5 Métrica
            p Son instrumentos que nos permiten interpretar una medición frente a una escala, es decir, a partir de una lectura permite identificar el estado actual del objeto evaluado.        
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder1.png', alt='Texto que describa la imagen')

    .titulo-sexto.color-acento-contenido
      h5 Figura 1 
      span Uso de las medidas, métricas y KPI 

    .row.justify-content-center.mb-4
      .col-md-10
        .row.align-items-center
          .col-md-7
            figure
              img(src='@/assets/curso/tema1/vec1.svg', alt='Texto que describa la imagen')
          .col-md-5
            p.mb-4 Estos conceptos permiten comprender mejor el ejercicio realizado, interpretar algunos resultados obtenidos, así como generar informes técnicos con datos coherentes y que pueden demostrar el estado actual de la seguridad de una aplicación web.
    separador

    #t_1_2.titulo-segundo.color-acento-contenido
      .h4 1.2 Infraestructura de aplicaciones web

    .row.justify-content-center.align-items-center.mb-4
      .col-md-8
        p.mb-4 Las aplicaciones web han ganado terreno en la adopción e implementación de soluciones para las organizaciones, dada su flexibilidad, compatibilidad, capacidades de gestionar información y sobre todo su rapidez para la implementación dado que requiere de una infraestructura centralizada, esto conlleva a facilitar también su mantenimiento; y, por otra parte, a los usuarios finales les significa accederlas desde cualquier dispositivo haciendo uso de un navegador web y estar conectados a una red local o internet.
        p.mb-4 En el siguiente recurso se presentan algunos de los componentes que integran una infraestructura de aplicaciones web, lo cual servirá para comprender mejor su funcionamiento:
      .col-md-4
        figure
          img(src='@/assets/curso/tema1/1.jpg', alt='Mujer animada con tablet')

    .row.justify-content-center.mb-4
      .col-md-10
        .row.justify-content-center.align-items-center.mb-4
          .col-md-2
            figure
              img(src='@/assets/curso/tema1/1.png', alt='icono')
          .col-md-10
            h5 Usuario
            p.mb-0 Es la persona u otra aplicación que realiza la solicitud de acceso a un recurso web,  de forma habitual en diferentes situaciones, diferenciando los aspectos entre el servicio, el producto y la persona.

        .row.justify-content-center.align-items-center.mb-4
          .col-md-2
            figure
              img(src='@/assets/curso/tema1/2.png', alt='icono')
          .col-md-10
            h5 Dispositivo de acceso
            p.mb-0 Es el dispositivo físico que utiliza el usuario para conectarse a una red y hacer uso de un navegador,  a través de computadores, portátiles, tabletas y dispositivos móviles entre otros.

        .row.justify-content-center.align-items-center.mb-4
          .col-md-2
            figure
              img(src='@/assets/curso/tema1/3.png', alt='icono')
          .col-md-10
            h5 Navegador web
            p.mb-0 Son programas que permiten navegar dentro de una red como lo es internet y visualizar recursos enriquecidos con texto, imágenes, videos, audio, hoy en día se cuenta con gran variedad de navegadores como, por ejemplo: Edge, Firefox, Chrome, Opera, Safari, Brave, entre otros.

        .row.justify-content-center.align-items-center.mb-4
          .col-md-2
            figure
              img(src='@/assets/curso/tema1/4.png', alt='icono')
          .col-md-10
            h5 Servidor Web
            p.mb-0 Es un programa especializado que se instala en un dispositivo hardware o virtual y que cuenta con recursos de procesamiento, almacenamiento, de tráfico y sirve para ofrecer alojamiento de recursos web.

        .row.justify-content-center.align-items-center.mb-4
          .col-md-2
            figure
              img(src='@/assets/curso/tema1/5.png', alt='icono')
          .col-md-10
            h5 Lenguajes de programación
            p.mb-0 Estos permiten programar la lógica de las aplicaciones web bajo el uso de lenguajes compilados o lenguajes intérpretes, dado que el lenguaje HTML no es de alto nivel y no permite programación a un nivel superior, se debe hacer uso de estos lenguajes para generar la lógica de negocio y comportamiento que debe se seguir una aplicación web.


        .row.justify-content-center.align-items-center.mb-4
          .col-md-2
            figure
              img(src='@/assets/curso/tema1/6.png', alt='icono')
          .col-md-10
            h5 Motor de base de datos
            p.mb-0 Este también es un programa que se aloja en un dispositivo hardware o virtual, y su función principal es la de almacenar la información de forma sistematizada, en estructuras organizadas como bases de datos, tablas y registros.

    p.mb-4 Todos estos componentes se interrelacionan para conformar las arquitecturas técnicas de aplicaciones web, en la siguiente figura, se aprecia su interrelación y flujo de información ante una solicitud de un recurso web.
    
    .titulo-sexto.color-acento-contenido
      h5 Figura 2
      span Arquitectura de una aplicación web

    


</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
