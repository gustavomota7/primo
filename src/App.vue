<template>
  <div id="app">
    <Video></Video>
    <Agenda></Agenda>
    <Upload></Upload>
  </div>
</template>

<script>
import Video from './components/Video.vue'
import Agenda from './components/Agenda.vue'
import Upload from './components/Upload.vue'

export default {
  name: 'App',
  components: {
    Video,
    Agenda,
    Upload
  }
}
</script>

<style>
#app {
  font-family: Montserrat, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background-color: #f3f3f3;
}

</style>
