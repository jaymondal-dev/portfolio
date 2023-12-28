<script>
    export let data;
</script>

<h1 class="my-4 md:bg-[#36a4c0] md:p-2 px-4 py-2 md:text-white text-slate-950 font-semibold text-4xl ">Blogs </h1>


<div class="md:m-20 lg:mx-60">
    {#each data.posts as post}
        <div class="flex justify-between items-center m-4 bg-[#caf0f8] rounded-md ">
            <div class="m-4">
                <ul>
                    <h2 class="text-xl text-slate-500 font-semibold py-2">
                        <a href={post.path}>
                            {post.meta.title}
                        </a>
                    </h2>
                    <p >By - {post.meta.author}
                    <p />
                    Published on: {post.meta.date}
                </ul>
            </div>
            <div class="bg-slate-100 rounded-md m-2">
                <img src={post.meta.image} alt={post.meta.title} class=" h-24 md:h-32 rounded-lg" />
            </div>
        </div>
    {/each}
</div>
