<template lang="pug">
nav
	NuxtLink.titulo(to="/") Inicio
	ul
		li
			NuxtLink(to='/clases') Mis clases
		li
			NuxtLink(to='/herramientas') Herramientas
		li
			NuxtLink(to='/aqui') Esta página
</template>

<style scoped>
	nav{
		padding-left: 1rem;
		background: darkorange;
		color: white;
		display: flex;
		line-height: 5rem;
		align-content: space-between;
		font-family: "Open sans", "Roboto", "arial", sans-serif;
		box-shadow: 0 2px 4px rgba(0,0,0,.3);
		margin-bottom: 2rem;
	}
	ul{
		display: flex;
	}
	ul, li{
		list-style: none;
		padding: 0;
		margin: 0;
	}
	a{
		display: inline-block;
		padding: 0 1rem;
		color: white;
		text-decoration: none;
	}
	a:hover{
		background: #0001;
	}
</style>