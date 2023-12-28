<script>
	export let data;
	const { title, date, Content } = data;
</script>

    <div class=" shadow-lg my-4 rounded-lg md:p-5 p-3 bg-[#ffffff] text-slate-700">
		<h1 class="text-3xl text-black">{data.title}</h1>
		<br />
		<p>Published: {data.date}</p>
		<p>Author: {data.author}</p>
	</div>

<article class="md:m-10 m-6">
	<br />
	<div class="md:mx-20 md:p-5 p-4">
		<svelte:component this={data.content} />
	</div>
</article>
