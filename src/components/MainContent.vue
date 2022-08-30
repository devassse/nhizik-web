<template>
  <div id="main" class="layout-row flex">
    <div id="content" class="flex">
      <div class="sr">
        <div class="page-hero page-container">
          <div class="media bg-media">
            <div class="hero-section media-content"></div>
          </div>
          <div class="p-5 pos-rlt text-center">
            <h1 class="display-3 font-weight-bold text-white mb-5 mx-5">
              Portal de Música Moçambicana
            </h1>
            <a href="#" class="btn btn-md gd-primary text-white no-ajax m-2">Descubra novas músicas</a>
            <a href="#" class="btn btn-md btn-outline-primary m-2">Baixar aplicação</a>
          </div>
        </div>
        <div class="page-container p-5 pos-rlt">
          <div class="text-center pt-5">
            <h2 class="display-4 font-weight-bold text-purple mb-5 pt-5">
              Conheça os Artistas
            </h2>
            <p>
              Encontre e conheça os Artistas, escuta e faça playlists das tuas
              músicas favoritas e partilhe todas emoções.
            </p>
            <div class="py-4">
              <a href="#" class="btn btn-md btn-outline-primary no-ajax m-2">Explorar artistas</a>
              <a href="#" class="btn btn-md btn-outline-primary m-2">Escutar agora (Streaming)</a>
            </div>
          </div>
        </div>
        <!-- Artists Slider -->
        <artists-slider></artists-slider>
      </div>
    </div>
  </div>
</template>

<script>
import ArtistsSlider from './ArtistsSlider.vue';
export default {
  components: { ArtistsSlider },
  setup() {
    return {
      
    };
  },
};
</script>

<style>
  /* Custom Styles to Hide Prev and Next Buttons in Carousel  */
.carousel-control-prev,
.carousel-control-next{
  border: 0;
  background-color: transparent;
}
</style>
