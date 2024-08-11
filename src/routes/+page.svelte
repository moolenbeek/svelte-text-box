<script lang="ts">
	let text: string = "";
</script>

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-5 py-5">
		<input class="input" title="Input (text)" type="search" bind:value={text} placeholder="type here" />
		<h1>{text || "some text"}</h1>
	</div>
</div>
