<template>
	<div class="todo-item" v-bind:class="{'is-complete':todo.completed}">
		<input type="checkbox" v-on:change="markComplete"/>
		<p>{{todo.title}}</p>
		<button class="del" @click="$emit('del-todo', todo.id)">X</button>
	</div>
</template>

<script>
	export default {
		name: "TodoItem",
		props: ["todo"],
		methods: {
			markComplete(){
				this.todo.completed = !this.todo.completed;
			}
		}
	}
</script>

<style>

</style>