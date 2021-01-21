<script lang="ts">
	import Tailwindcss from './tailwindCSS/tailwindcss.svelte';
	import Illustration from './units/illustration.svelte'
	import Title from './units/title.svelte'
	import TagLine from './units/tagline.svelte'
	import ValueProposition from './units/valueProposition.svelte'
</script>
<style>
</style>
<Tailwindcss />
<main class="text-center min-w-screen min-h-screen flex items-center justify-center text-white bg-black">
	<div class="m-8">
		<Illustration />
		<Title />
		<TagLine />
		<ValueProposition />
	</div>
</main>