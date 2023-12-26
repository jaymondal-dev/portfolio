<script>
    export let data;
</script>

<h1 class="my-4 md:bg-slate-600 p-2 md:text-white text-violet-500 font-semibold text-2xl ">Blogs</h1>

<div class="m-20">
    {#each data.posts as post}
        <div class="flex justify-between items-center m-4 border-2 border-slate-400 rounded-md shadow-lg">
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
            <div class="bg-slate-100 p-2 rounded-md m-2">
                <img src={post.meta.image} alt={post.meta.title} />
            </div>
        </div>
    {/each}
</div>
