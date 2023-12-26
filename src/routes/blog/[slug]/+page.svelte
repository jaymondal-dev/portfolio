<script>
	export let data;
	const { title, date, Content } = data;
</script>

<article class="m-10">
	<div class="border-2 border-black rounded-lg p-5  bg-[#2a3049] text-[#b2b2b2]">
		<h1 class="text-3xl text-white">{data.title}</h1>
		<br />
		<p>Published: {data.date}</p>
		<p>Author: {data.author}</p>
	</div>

	<br />
	<div class="mx-20 p-5 ">
		<svelte:component this={data.content} />
	</div>
</article>
