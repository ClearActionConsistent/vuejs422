<template>
	<div class="todo-item" v-bind:class="{'is-complete':todo.completed}">
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