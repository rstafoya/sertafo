<template lang="pug">
nav
	NuxtLink.titulo(to="/") Inicio
	ul
		li
			NuxtLink(to='/clases') Mis clases
		li
			NuxtLink(to='/aqui') Esta página
</template>

<style scoped>
	nav{
		border-radius: 10px;
		padding-left: 1rem;
		background: darkorange;
		color: white;
		display: flex;
		line-height: 3rem;
		align-content: space-between;
		font-family: "Open sans", "Roboto", "arial", sans-serif;
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