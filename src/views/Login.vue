<template>
    <div class="login">
        <div class="logo">
            <img class="logo" src="../assets/logo.png">
        </div>
        <div class="textbox">
			<div class="label">
				<h3>LOGIN</h3>
			</div>

			<div class="row">
				<div class="col">
					<input type="email" class="form-control form-control-lg estilo" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="E-mail">
				</div>
			</div>

			<div class="button">
				<router-link to="/home" tag="button" class="btn btn-primary estilo">Entrar</router-link>
			</div>
        </div>
		<div class="aviso">
			<p>A plataforma será liberada dia 10 de março, às 09h55</p>
		</div>
		<div class="fundo1">
			<img class="bola" src="../assets/supesq.png">
		</div>
		<div class="fundo2">
			<img class="bola" src="../assets/infesq.png">
		</div>
		<div class="fundo3">
			<img class="bola" src="../assets/supdir.png">
		</div>
		<div class="fundo4">
			<img class="bola" src="../assets/infdir.png">
		</div>
    </div>

</template>


<style scoped>

@font-face {
	font-family: 'globotipo_roundedregular';
	src: url('../fonts/globotiporounded-regular-webfont.woff2') format('woff2'),
		url('../fonts/globotiporounded-regular-webfont.woff') format('woff');
	font-weight: normal;
	font-style: normal;
}



.login {
    position: absolute;
    background-image: url("../assets/loginbg.png");
    background-size: 100% 100%;
    width: 100%;
    height: 100%;
}

.logo {
    position: relative;
    max-height: 150px;
    top: 20%;
}

h3 {
    color: white;
    font-weight: bold;
}

.textbox {
	display: flex;
	flex-direction: column;
    position: relative;
	justify-content: center;
	align-content: center;
    top: 30%;
}

.button {
	padding-top: 20px;
}

.form-control {
	display: inline;
	width: 50%;
	min-width: 420px;
}

.estilo {
	border-radius: 30px;
	background: white;
	color: black;
	border: none;
	padding: 10px;
	padding-left: 30px;
	padding-right: 30px;
}

.aviso {
	position: relative;
	color: white;
	top: 30%;
	font-size: 1.5rem;
	padding: 50px;
}

.fundo1 {
	position: absolute;
	top: 0;
	left: 0;
}

.fundo2 {
	position: absolute;
	bottom: 0;
	left: 0;
}

.fundo3 {
	position: absolute;
	top: 0;
	right: 0;
}

.fundo4 {
	position: absolute;
	bottom: 0;
	right: 0;
}

.bola {
	width: 500px;
}

@media (max-width: 1500px) {
	.bola {
		width: 300px;
	}
}

@media (max-width: 1000px) {
	.logo {
		max-height: 100px;
		margin-bottom: 50px;
	}

	.bola {
		width: 200px;
	}
}

</style>