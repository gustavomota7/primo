<template>
    <div class="box container-fluid">
        <div class="logo container-fluid">
            <img class="logo" src="../assets/logo.png">
        </div>
        <iframe src="https://www.youtube.com/embed/ly0wf5P5ywk" 
        title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; 
        clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="bg-color"></div>
    </div>
</template>

<style scoped>
.logo {
    padding: 25px;
    width: 100%;
    max-width: 500px;
}

iframe {
    width: 100%;
    max-width: 53vw;
    height: 30vw; 
}

h1 {
    padding: 50px;
}

.box {
    position: relative;
    padding: 0;
    padding-bottom: 5vw;
}

.bg-color {
    position: absolute;
    background: url("../assets/gradient.png"), #ff5f00;
    background-size: 100% 100%;
    width: 100%;
    height: 100%;
    top: 0;
    z-index: -1;
    clip-path: polygon(0 0, 100% 0, 100% 75%, 0% 100%);
    -webkit-backface-visibility: hidden;
}



</style>