<template>
	<v-app>
		<link rel='icon' href='../assets/favicon.ico' />
		<div id='app'>
			<router-view />
		</div>
	</v-app>
</template>

<style>

#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
    height: 100%;
}

/* @font-face { 
    font-family: Pacifico;
    src: url("../src/fonts/Pacifico-Regular.ttf") format("truetype"); 
} */

</style>
