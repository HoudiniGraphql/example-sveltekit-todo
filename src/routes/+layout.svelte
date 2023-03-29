<svelte:head>
	<title>Houdini • SvelteKit • TodoMVC</title>
	<link rel="stylesheet" href="//unpkg.com/todomvc-common/base.css" />
	<link rel="stylesheet" href="//unpkg.com/todomvc-app-css/index.css" />
</svelte:head>

<section class="todoapp">
	<slot />
</section>

<footer class="info">
	<p>Double-click to edit a todo</p>
	<p>
		Created by <a href="https://github.com/AlecAivazis">Alec Aivazis</a> with
		<a href="https://github.com/HoudiniGraphql/houdini">Houdini</a>
	</p>
	<p>Part of <a href="http://todomvc.com">TodoMVC</a></p>
</footer>
