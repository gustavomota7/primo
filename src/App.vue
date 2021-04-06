<template>
  <div id="app">
    <Video></Video>
    <Agenda></Agenda>
    <Upload></Upload>
    <Depos></Depos>
    <Footer></Footer>
  </div>
</template>

<script>
import Video from './components/Video.vue'
import Agenda from './components/Agenda.vue'
import Upload from './components/Upload.vue'
import Depos from './components/Depos.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Video,
    Agenda,
    Upload,
    Depos,
    Footer
  }
}
</script>

<style>

@font-face {
    font-family: 'globotipo_roundedregular';
    src: url('fonts/globotiporounded-regular-webfont.woff2') format('woff2'),
         url('fonts/globotiporounded-regular-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}

#app {
  font-family: globotipo_roundedregular;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background-color: #f3f3f3;
}

</style>
