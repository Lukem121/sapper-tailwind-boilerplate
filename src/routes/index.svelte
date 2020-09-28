<script>
	import { onMount } from "svelte";
	onMount(async () => {
		const { default: tippy } = await import("tippy.js");
		tippy('#myButton', {
			content: "I'm a Tippy tooltip!",
		});
	});
</script>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<div>
	<h1>Svelte + Sapper + Tailwind + Tippy.js (Tool tip) Boilerplate</h1>
</div>

