<template>
    <div class="box container-fluid">
        <div class="logo container-fluid">
            <img class="logo" src="../assets/logo.png">
        </div>
        <iframe src="https://www.youtube.com/embed/4eoM26ZmHd0" 
        title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; 
        clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="bg-color"></div>
        <div class="fundo1">
			<img class="bola" src="../assets/supesq2.png">
		</div>
		<div class="fundo2">
			<img class="bola" src="../assets/infesq2.png">
		</div>
		<div class="fundo3">
			<img class="boladir" src="../assets/infdir2.png">
		</div>
    </div>
</template>

<style scoped>
.logo {
    padding: 25px;
    width: 100%;
    max-width: 500px;
    z-index: 2;
}

iframe {
    width: 100%;
    max-width: 53vw;
    height: 30vw;
    z-index: 2;
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

.fundo1 {
	position: absolute;
	top: 0;
	left: 0;
    z-index: -1;
}

.fundo2 {
	position: absolute;
	bottom: -20%;
	left: 5%;
    z-index: -1;
}

.fundo3 {
	position: absolute;
	bottom: 0;
	right: 0;
    z-index: -1;
}

.bola {
	width: 300px;
}

.boladir {
	width: 400px;
}

@media (max-width: 800px) {
    iframe {
        max-width: 80vw;
        height: 45vw;
    }

    .box {
        padding-bottom: 40vw;
    }

    .fundo2 {
        bottom: 0%;
        left: 50%;
        transform: translateX(-50%);
    }

    .fundo3 {
        display: none;
    }
}

@media (max-width: 550px) {
    .fundo2 {
        display: none;
    }

    .box {
        padding-bottom: 5vw;
    }
}

</style>