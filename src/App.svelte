<script>
  import Tailwindcss from "./Tailwindcss.svelte";

	let name = 'world';
</script>

<Tailwindcss />

<button class="button ~positive !normal">Hello {name}!</button>
