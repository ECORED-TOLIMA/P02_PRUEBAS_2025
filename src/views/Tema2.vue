<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Propuestas
    
    
    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1 Tarjeta libro
    .row.justify-content-center.align-items-center.mb-3
      .col-lg-4
        .card-section
          .card
            .flip-card
              .flip-card__container
                .card-front
                  .card-front__tp.card-front__tp--city
                    img(src='@/assets/curso/temas/tarjetas/conectada_02.svg', alt='')
                    h2.card-front__heading City break
                    .card-front__text-price
                      | From £29
                  .card-front__bt
                    p.card-front__text-view View me
            .inside-page
              .inside-page__container
                h3 For urban lovers
                p.inside-page__text
                  As cities never sleep, there are always something going on, no matter what time!
                a.boton.inside-page__btn.inside-page__btn--city(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | View deals
      .col-lg-4
        .card-section
          .card
            .flip-card
              .flip-card__container
                .card-front
                  .card-front__tp.card-front__tp--ski
                    img(src='@/assets/curso/temas/tarjetas/conectada_02.svg', alt='')
                    h2.card-front__heading City break
                    .card-front__text-price
                      | From £29
                  .card-front__bt
                    p.card-front__text-view View me
            .inside-page
              .inside-page__container
                h3 For urban lovers
                p.inside-page__text
                  As cities never sleep, there are always something going on, no matter what time!
                a.boton.inside-page__btn.inside-page__btn--ski(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | View deals
      .col-lg-4
        .card-section
          .card
            .flip-card
              .flip-card__container
                .card-front
                  .card-front__tp.card-front__tp--beach
                    img(src='@/assets/curso/temas/tarjetas/conectada_02.svg', alt='')
                    h2.card-front__heading City break
                    .card-front__text-price
                      | From £29
                  .card-front__bt
                    p.card-front__text-view View me
            .inside-page
              .inside-page__container
                h3 For urban lovers
                p.inside-page__text
                  As cities never sleep, there are always something going on, no matter what time!
                a.boton.inside-page__btn.inside-page__btn--beach(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | View deals

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
