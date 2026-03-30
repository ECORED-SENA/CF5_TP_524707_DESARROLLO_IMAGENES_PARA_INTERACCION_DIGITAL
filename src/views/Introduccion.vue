<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p.mb-5 El desarrollo de interfaces digitales constituye un proceso estratégico dentro de la producción multimedia, ya que permite estructurar entornos visuales orientados a facilitar la interacción entre el usuario y el sistema. En este contexto, el diseño no se limita a la apariencia gráfica, sino que integra decisiones relacionadas con la organización de la información, la jerarquía visual, la claridad comunicativa y la funcionalidad interactiva. Esta articulación favorece la comprensión del contenido y contribuye a la continuidad de la experiencia de uso dentro de los entornos digitales. 
    .caja-intro.mb-5(data-aos="zoom-in")
      .row.align-items-center
        .col-xl-auto
          figure
            img(src='@/assets/curso/intro/img1.png', alt='').m-auto
        .col-xl
          p.mb-0 Asimismo, la configuración visual de una interfaz se fundamenta en la definición previa de una identidad gráfica que oriente la selección coherente de colores, tipografías, estilos de iconografía y criterios compositivos. La consolidación de una línea gráfica permite mantener unidad estética a lo largo del producto digital y facilita la integración progresiva de nuevos contenidos sin afectar la coherencia del sistema. De esta manera, la identidad visual se convierte en un elemento organizador que fortalece la orientación del usuario y favorece la interpretación funcional del entorno multimedia.
    .caja-intro-1(data-aos="zoom-in")
      p.mb-0 En este marco, el análisis de referentes aplicados, como plataformas digitales orientadas a la reproducción de contenidos audiovisuales, permite comprender cómo la articulación entre estructura gráfica, recursos visuales y criterios interactivos contribuye a consolidar experiencias de uso organizadas y comprensibles. La disposición jerárquica de los elementos, el uso estratégico del color y la integración equilibrada de imágenes e iconos evidencian la importancia de planificar de manera anticipada el diseño visual, con el propósito de optimizar la navegación y fortalecer la comunicación dentro de los productos multimedia contemporáneos. 
</template>

<script>
export default {
  name: 'Introduccion',
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
