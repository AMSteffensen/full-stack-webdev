<script>
    import TodoItem from "$lib/todo-item.svelte";

    const title = 'Todos | New';
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1>

<form action="" method="" >
     <input type="text" name="text" aria-label="Add a todo" placeholder="+ to add a new todo">
</form>

<TodoItem />

<TodoItem />

<TodoItem />