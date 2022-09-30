<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p.mb-4(data-aos="fade-right") Le damos la bienvenida al componente formativo denominado <b>Metodologías, normas y estándares de seguridad orientada a aplicaciones web,</b> el cual hace parte del programa de formación técnico en “Seguridad en aplicaciones web”, para lo cual se invita a observar el siguiente video:
    
    figure.mb-5(data-aos="fade-up")
      .video
        iframe(width="942" height="530" src="https://www.youtube.com/embed/5Nk-Td6QLVw" title="Metodologías, normas y estándares de seguridad orientada a aplicaciones web" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
   
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
