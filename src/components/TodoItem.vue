<template>
	<div id="app">
		<h3>{{todo.title}}</h3>
	</div>
</template>

<script>
	export default {
		name: "TodoItem",
		props: ["todo"]
	}
</script>

<style>

</style>