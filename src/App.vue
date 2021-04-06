<template>
	<div id="app">
		<router-view/>
	</div>
</template>

<style>

@font-face {
	font-family: 'globotipo_roundedregular';
	src: url('./fonts/globotiporounded-regular-webfont.woff2') format('woff2'),
		url('./fonts/globotiporounded-regular-webfont.woff') format('woff');
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

#nav {
	padding: 30px;
}

#nav a {
	font-weight: bold;
	color: #2c3e50;
}

#nav a.router-link-exact-active {
	color: #42b983;
}
</style>
