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

    .row.justify-content-center.align-items-center.mb-4
      .col-md-6
        figure
          img(src='@/assets/curso/tema1/img1.svg', alt='icono')
      .col-md-5
        .tarjeta.tarjeta-color1.p-5
          ol.lista-ol
            li 
              span.text-bold a. 
              | El usuario realiza la solicitud de un recurso web a través de un navegador.
            li 
              span.text-bold b. 
              | El navegador realiza la petición del recurso web a través del protocolo http.
            li 
              span.text-bold c. 
              | El servidor web recibe la petición y procesa la respuesta:
            li  
              ul.lista-ul--color
                li 
                  i.fas.fa-angle-right
                  | Procesa lógica de negocio.
                li 
                  i.fas.fa-angle-right
                  | Procesa información desde bases de datos.
                li 
                  i.fas.fa-angle-right
                  | Conforma la respuesta.
            li 
              span.text-bold d. 
              | El servidor devuelve la respuesta hacia el navegador.
            li 
              span.text-bold e. 
              | Navegador despliega resultado al usuario.

    p.mb-4 Actualmente existen diferentes tipos de aplicaciones web, entre las más comunes se resaltan:

    .row.justify-content-center.align-items-center.mb-4
      .col-md-4
        figure
          img(src='@/assets/curso/tema1/7.jpg', alt='icono')
      .col-md-8
        TabsA.color-acento-contenido.mb-5
          .tarjeta.color-acento-contenido--borde.p-4(titulo="Hogar inteligente")
            h5 Hogar inteligente
            p Termostatos domésticos, control de televisores, detectores de humo, cámaras de seguridad, cafeteras y otros electrodomésticos.


          .tarjeta.color-acento-contenido--borde.p-4(titulo="Fuera del hogar")
            h5 Fuera del hogar
            p.mb-4 Automóviles en red, prendas tecnológicas y monitores de salud en la ropa, aplicaciones para ciclistas para controlar su actividad física, gafas inteligentes.

          .tarjeta.color-acento-contenido--borde.p-4(titulo="Ropa tecnológica (wearables)")
            h5 Ropa tecnológica (wearables)
            p Dispositivos médicos, productos de salud, marcapasos y bombas de insulina. Estos wearables monitorean la geolocalización, así como la frecuencia cardiaca, el pulso, calorías, patrones del sueño, etc.

          .tarjeta.color-acento-contenido--borde.p-4(titulo="Transporte")
            h5 Transporte
            p Supervisión de vehículos conectados, sensores de proximidad, parqueo de vehículos, vehículos autónomos, control remoto de peajes.
        
          .tarjeta.color-acento-contenido--borde.p-4(titulo="Contadores inteligentes")
            h5 Contadores inteligentes
            p Dispositivos electrónicos de medición de energía, calefacción, climatización, agua.

    p.mb-4 Comprender la arquitectura técnica que sirven las aplicaciones web, así como sus tipos, permitirá comprender el funcionamiento y determinar un ejercicio que facilite el aseguramiento de las aplicaciones web.

    separador

    #t_1_3.titulo-segundo.color-acento-contenido
      .h4 1.3	Normatividad y estándares para la gestión de la seguridad

    p.mb-4 La gestión de la seguridad en las aplicaciones web es una tarea que actualmente no se le presta la debida atención, y esta no depende únicamente de las buenas prácticas de programación de software, en su lugar es importante tener presente que la responsabilidad de poseer una aplicación web pública, que gestione información importante para la organización o maneje información confidencial, y ello obliga a contar con ciertos controles de seguridad que garantice los pilares de la seguridad de la información, a saber:

    .row.justify-content-center.align-items-center.mb-4
      .col-md-10
        figure
          img(src='@/assets/curso/tema1/vec2.svg', alt='icono')

    p.mb-4 Ahora bien, para cumplir con estos tres pilares se hace necesario de acciones, y aquí es donde han surgido algunas buenas iniciativas como normatividad, estándares y buenas prácticas para una adecuada gestión de la información, entre las cuales poder revisar:
    
    .row.mb-4
      .col-md-3
        .tarjeta.clr-1
          h4.text-center.p-2 Norma ISO/IEC 27001:2013:

    p.mb-4 Ahora bien, para cumplir con estos tres pilares se hace necesario de acciones, y aquí es donde han surgido algunas buenas iniciativas como normatividad, estándares y buenas prácticas para una adecuada gestión de la información, entre las cuales poder revisar:

    .row.justify-content-center.align-items-center.mb-4
      .col-md-10.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/7.png' alt='AvatarTop')
          .tarjeta.clr-2
            .p-5
              ul.lista-ul--color.mb-0
                li 
                  i.fas.fa-angle-right
                  | Concientización de la necesidad de adoptar una cultura de seguridad.
                li 
                  i.fas.fa-angle-right
                  | Delegación de responsabilidades sobre la seguridad de la información.
                li 
                  i.fas.fa-angle-right
                  | Involucrar la alta dirección en la estrategia de seguridad.
                li 
                  i.fas.fa-angle-right
                  | Seleccionar los controles adecuados para garantizar la seguridad de la información.
                li 
                  i.fas.fa-angle-right
                  | Adoptar la seguridad como elemento esencial de los sistemas de información.
                li 
                  i.fas.fa-angle-right
                  | Adoptar estrategias activas para la prevención de incidentes de seguridad activa.
                li 
                  i.fas.fa-angle-right
                  | Adoptar la mejora continua en la evaluación de la seguridad.

    p.mb-4 En cuanto a la metodología para la adopción de esta norma, se incorpora el ciclo PDCA, acrónimo del inglés Plan-Do-Check-Act (en español: PHVA, planear, actuar verificar y actuar) la cual incorpora los siguientes ítems como se puede apreciar en la siguiente figura. 

    .titulo-sexto.color-acento-contenido
      h5 Figura 3
      span Fases de un SGSI

    .row.justify-content-center.align-items-center.mb-4
      .col-md-12
        .tarjeta.clr--gris1
          .p-5
            .row.justify-content-center.align-items-center
              .col-md-7
                ImagenInfografica.color-secundario.m-5
                  template(v-slot:imagen)
                    figure
                      img.mb-0(src='@/assets/curso/tema1/info1.svg', alt='Texto que describa la imagen')

                  .tarjeta.color-info.p-5(x="71%" y="9%" numero="")
                    ol.lista-ol--cuadro
                      li 
                        .lista-ol--cuadro__vineta
                          span 1
                        | Diseñar SGSI.
                      li 
                        .lista-ol--cuadro__vineta
                          span 2
                        | Análisis de procesos.
                      li 
                        .lista-ol--cuadro__vineta
                          span 3
                        | Definir Alcance.
                      li 
                        .lista-ol--cuadro__vineta
                          span 4
                        | Elaborar política de seguridad.
                      li 
                        .lista-ol--cuadro__vineta
                          span 5
                        | Identificar y evaluar inventario de activos.
                      li 
                        .lista-ol--cuadro__vineta
                          span 6
                        | Realizar análisis de riesgos.
                      li 
                        .lista-ol--cuadro__vineta
                          span 7
                        | Generar SoA.

                  .tarjeta.color-info.p-5(x="72%" y="78%" numero="")
                    ol.lista-ol--cuadro
                      li 
                        .lista-ol--cuadro__vineta
                          span 8
                        | Generar plan de mitigación de riesgos.
                      li 
                        .lista-ol--cuadro__vineta
                          span 9
                        | Aplicar plan de mitigación de riesgos.
                      li 
                        .lista-ol--cuadro__vineta
                          span 10
                        | Implementar controles seleccionados.
                      li 
                        .lista-ol--cuadro__vineta
                          span 11
                        | Administración de cambio.

                  .tarjeta.color-info.p-5(x="16%" y="78%" numero="")
                    ol.lista-ol--cuadro
                      li 
                        .lista-ol--cuadro__vineta
                          span 12
                        | Revisiones gerenciales.
                      li 
                        .lista-ol--cuadro__vineta
                          span 13
                        | Revisiones independientes.
                      li 
                        .lista-ol--cuadro__vineta
                          span 14
                        | Auditorías internas.
                      li 
                        .lista-ol--cuadro__vineta
                          span 15
                        | Revisiones técnicas.

                  .tarjeta.color-info.p-5(x="17%" y="9%" numero="")
                    ol.lista-ol--cuadro
                      li 
                        .lista-ol--cuadro__vineta
                          span 16
                        | Implementar mejoras.
                      li 
                        .lista-ol--cuadro__vineta
                          span 17
                        | Tomar acciones preventivas y correctivas.
                      li 
                        .lista-ol--cuadro__vineta
                          span 18
                        | Comunicar resultados de las acciones tomadas.

    p.mb-4 Ahora bien, este estándar es base para la adopción de un SGSI, lo que conlleva a que, si una organización esta certificada o está pensando en certificar sus procesos bajo esta norma, debe tener presente la seguridad de la información que se gestiona a través de aplicaciones web, de acuerdo con las siguientes recomendaciones:

    .row.justify-content-center.align-items-center.mb-4
      .col-md-5
        .tarjeta.color-amarillo.p-4
          ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta
                span 01
            p Los elementos y componentes de las aplicaciones web deberán ser objeto de análisis, planificación y evaluación para que sean cubiertos por el SGSI, esto involucra que también se le haga un análisis de riesgos.
      .col-md-5
        .tarjeta.color-amarillo.p-4
          ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta
                span 02
            p Dado el cambio continuo tecnológico, se requiere que las aplicaciones web sean evaluadas permanentemente según los nuevos retos, tecnologías y amenazas.

    .row.mb-4
      .col-md-3
        .tarjeta.clr-1
          h4.text-center.p-2 Norma ISO/IEC 27002:2013:

    p.mb-0 Este estándar establece una guía para la implementación de controles de seguridad en una organización, a partir de sus objetivos, controles y estrategias de implementación.
    p.mb-4 Este estándar está compuesto por 14 dominios, 35 objetivos de control y 114 controles, con los cuales se busca adoptar medidas de seguridad en una organización.
    p.mb-4 A continuación, se exponen algunos de los controles asociados directamente con la seguridad de la información en aplicaciones web:

    .row.justify-content-center.mb-5
      .col-lg-10.position-relative
        .crd.crd--avatarHorizontal.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src='@/assets/curso/tema1/8.png' alt='AvatarTop').img1
            .col
              ul.lista-ul--color.mb-0
                li 
                  i.fas.fa-angle-right
                  | Documento con política de seguridad de la información.
                li 
                  i.fas.fa-angle-right
                  | Asignación de responsabilidades relativas a la seguridad.
                li 
                  i.fas.fa-angle-right
                  | Formación y concienciación sobre la seguridad de la información.
                li 
                  i.fas.fa-angle-right
                  | Notificación de los eventos de seguridad de la información.
                li 
                  i.fas.fa-angle-right
                  | Gestión de los derechos de propiedad intelectual.
                li 
                  i.fas.fa-angle-right
                  | Protección de activos de documentación de la organización.
                li 
                  i.fas.fa-angle-right
                  | Protección de datos y privacidad de la información de carácter sensible de índole personal.
              
    p.mb-4 Desde el punto de vista de aporte de este estándar en la seguridad web, se pueden referenciar algunas medidas importantes que ayudan a gestionar la seguridad de los datos en las aplicaciones web, así:

    .tarjeta.tarjeta-color.p-5.mb-5
      SlyderA(tipo="b")
        .row
          .col-md-6.mb-4.mb-md-0
            h5 Control de acceso al código fuente
            p Se debe gestionar la seguridad del código fuente, las personas que acceden a partir de medidas de protección.
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder6.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h5 Procedimientos de control de cambios
            p.mb-4 Cualquier cambio realizado en un sistema puede afectarlo negativamente, se sugieren una serie de recomendaciones para la gestión del control de cambios.
            p.mb-4 Para conocer una serie de recomendaciones para la gestión del control de cambios, haz clic en el botón 
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder7.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h5 Revisión técnica tras cambios en las plataformas
            p Todo sistema deberá ser evaluado después de la aplicación de los cambios, para verificar que no existan fallas.        
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder8.png', alt='Texto que describa la imagen')
  
        .row
          .col-md-6.mb-4.mb-md-0
            h5 Fugas de información
            p Se deben evitar que sucedan fugas de información a partir de la inadecuada aplicación de cambios en los sistemas de información, es necesario adoptar los controles para la detección de fugas.         
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder9.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h5 Desarrollo externo de aplicaciones
            p Si la organización considera el desarrollo por terceros o externos, se deberá velar porque cumpla con las condiciones y requisitos de seguridad y teniendo en cuenta las condiciones de propiedad intelectual, calidad del desarrollo, certificaciones, entre otros.        
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder10.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h5 Gestión de vulnerabilidades
            p.mb-4 Se deben adoptar mecanismos y planes para la gestión de vulnerabilidades en cualquier desarrollo o cambio realizado.
            p.mb-3 Haz clic en el botón Ver más, para conocer qué se debe hacer antes de ser puesto en producción. 
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/slyder11.png', alt='Texto que describa la imagen')

    .row.mb-4
      .col-md-3
        .tarjeta.clr-1
          h4.text-center.p-2 Norma ISO/IEC 25010:2013: 

    p.mb-4 Este estándar aplica para la industria del desarrollo de software, así como para las organizaciones que realizan desarrollos propios para gestionar su información, es así como esta norma busca mejorar la calidad en los productos de desarrollo de software a partir de las siguientes características:

    .row 
      .col-md-12
        TabsA.color-acento-contenido.mb-5
          .tarjeta.color-acento-contenido--borde.p-4(titulo="Adecuación funcional del software")
            h5 Adecuación funcional del software 
            p El sistema satisface las necesidades declaradas cuando se utiliza en condiciones específicas.
            .row.justify-content-center  
              .col-md-5
                figure
                  img(src='@/assets/curso/tema1/calidad.jpg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-contenido--borde.p-4(titulo="Eficiencia del desempeño del software")
            h5 Eficiencia del desempeño del software 
            p.mb-4 Automóviles en red, prendas tecnológicas y monitores de salud en la ropa, aplicaciones para ciclistas para controlar su actividad física, gafas inteligentes.
            .row.justify-content-center  
              .col-md-5
                figure
                  img(src='@/assets/curso/tema1/calidad.jpg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-contenido--borde.p-4(titulo="Compatibilidad")
            h5 Compatibilidad 
            p Necesidad del producto final para funcionar ante diferentes características de software y hardware.
            .row.justify-content-center  
              .col-md-5
                figure
                  img(src='@/assets/curso/tema1/calidad.jpg', alt='Texto que describa la imagen')
  
          .tarjeta.color-acento-contenido--borde.p-4(titulo="Usabilidad ")
            h5 Usabilidad 
            p Donde entra en juego la interfaz y experiencia de usuario para aprender a usar rápidamente el software.
            .row.justify-content-center  
              .col-md-5
                figure
                  img(src='@/assets/curso/tema1/calidad.jpg', alt='Texto que describa la imagen')
             
          .tarjeta.color-acento-contenido--borde.p-4(titulo="Contadores inteligentes")
            h5 Confiabilidad
            p Se basa en evaluar la capacidad del sistema para trabajar sin fallas durante un periodo de tiempo específico en un entorno específico.
            .row.justify-content-center  
              .col-md-5
                figure
                  img(src='@/assets/curso/tema1/calidad.jpg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-contenido--borde.p-4(titulo="Ropa tecnológica (wearables)")
            h5 Seguridad 
            p Nos ayuda a analizar y verificar la seguridad de nuestro producto software mediante diferentes pruebas como: pruebas de penetración, vulnerabilidad, ethical hacking o static analysis.
            .row.justify-content-center  
              .col-md-5
                figure
                  img(src='@/assets/curso/tema1/calidad.jpg', alt='Texto que describa la imagen')
  
          .tarjeta.color-acento-contenido--borde.p-4(titulo="Transporte")
            h5 Mantenibilidad
            p El sistema debe ser fácil de mantener, analizarlo, cambiarlo y probarlo. 
            .row.justify-content-center  
              .col-md-5
                figure
                  img(src='@/assets/curso/tema1/calidad.jpg', alt='Texto que describa la imagen')
    
          .tarjeta.color-acento-contenido--borde.p-4(titulo="Portabilidad")
            h5 Portabilidad
            p Esto se refiere a la capacidad que tiene el producto software para cambiar entre versiones de un sistema operativo a otro sin mayores complicaciones.
            .row.justify-content-center  
              .col-md-5
                figure
                  img(src='@/assets/curso/tema1/calidad.jpg', alt='Texto que describa la imagen')

    p.mb-4 Esto fortalece los procesos de desarrollo de software dentro las organizaciones y en los procesos de desarrollo en sitio en las organizaciones, que buscan mejorar los niveles de seguridad.
    p.mb-4 Para reforzar esta temática, se sugiere observar el siguiente video.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    separador

    #t_1_4.titulo-segundo.color-acento-contenido
      .h4 1.4	Metodologías para la gestión de la seguridad en aplicaciones web

    .row.justify-content-center.align-items-center.mb-4
      .col-md-8
        p.mb-4 Existen normas y estándares que orientan en la adopción de iniciativas de seguridad en las organizaciones y que impactan directamente en la seguridad de las aplicaciones web y en la información gestionada a través de ellos, ahora bien, desde el punto de vista práctico existen iniciativas metodológicas para la gestión de las vulnerabilidades en aplicaciones web específicamente, una de ellas es Owasp.
        p Owasp (Open Web Application Security Project) es una metodología de seguridad para la auditoría web, orientada al análisis de seguridad de estas aplicaciones. Esta metodología está siendo utilizada en la mayoría de los trabajos de auditoría de seguridad, ya que permite a partir de la auditoría realizar una evaluación de riesgos.
      .col-md-4
        figure
          img(src='@/assets/curso/tema1/9.png', alt='Texto que describa la imagen')

    p.mb-4 Parte de la revisión de los controles definidos por la metodología, la cual permite al auditor garantizar que una revisión de la plataforma se realiza de forma adecuada, garantizando que todos los vectores de ataque han sido analizados y que los fallos de seguridad han sido detectados. 
    p.mb-5 Este proceso ayuda a mejorar la seguridad y la protección de los sistemas informáticos en las organizaciones.

    .titulo-sexto.color-acento-contenido
      h5 Figura 4
      span Flujo de trabajo de prueba SDLC genérico

    .row.justify-content-center.align-items-center.mb-4
      .col-md-10
        figure
          img(src='@/assets/curso/tema1/vec3.svg', alt='Texto que describa la imagen')

    p.mb-4 Actualmente la mayoría de los desarrolladores de software no realizan la validación de vulnerabilidades en sus productos si no hasta que este ya es funcional, pero esto no es tan eficiente, por ello se sugiere la adopción de un Ciclo de Vida de Desarrollo de Software (SDLC), el cual lleva a tener presente el factor de seguridad en cada una de las fases del desarrollo, así:

    .row.justify-content-center.align-items-center.mb-4
      .col-md-10
        .tarjeta.color-cuadro.p-4
          .row.justify-content-center.align-items-center
            .col-md-12
              p.mb-4 Con la adopción de los SDLC o Ciclo de Vida de Desarrollo de Software, se busca que el factor de la seguridad esté presente desde el momento de la concepción del software permitiendo identificar los requisitos funcionales de la necesidad que motiva la creación de una aplicación, mantener los componentes seguros desde el diseño y prototipado, buenas prácticas de programación, desarrollar un plan de pruebas de seguridad, así como mantener un plan de mantenimiento y actualizaciones que garanticen su funcionalidad y seguridad de la información en el tiempo, como se puede apreciar en la siguiente figura. 
            .col-md-6
              figure
                img(src='@/assets/curso/tema1/vec4.svg', alt='Texto que describa la imagen')

        a.anexo.mb-4.mb-lg-0(href="https://en.wikipedia.org/wiki/Main_Page" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p Anexo. Consideraciones generales de tratamiento clínico del paciente con COVID-19 en el servicio de urgencias
            
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
