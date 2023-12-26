

  <script>
    export let y;

    export let tabs = [
        { name: "About me", link: "/" },
        { name: "Projects ", link: "/projects" },
        { name: "Blog", link: "/blog" },
        // { name: "Contact", link: "" },
        // {name: '', link: ''},
    ];
</script>

<header
    class={"sticky z-[10] top-0 duration-200 px-6 flex items-center justify-between border-b border-solid " +
        (y > 0
            ? " py-4 bg-white border-slate-500"
            : " py-6 bg-transparent border-transparent")}
    
>
    <h1 class="font-medium text-2xl text-slate-950">
        <b class="Ubuntu">Jay Mondal</b> <span class=""></span>
    </h1>
    <div class="sm:flex items-center gap-6 hidden">
        {#each tabs as tab, index}
            <a
                href={tab.link}
                class="duration-200 hover:text-violet-500 hover:underline"
                target={index === 2 ? "_blank" : ""}
            >
                <p>{tab.name}</p>
            </a>
        {/each}
        <!-- <button
            class="blueShadow relative overflow-hidden px-5 py-2 group rounded-full bg-violet-600 text-white"
        >
            <div
                class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
            />
            <h4 class="relative z-9">Login</h4>
        </button> -->
        <button
            class="blueShadow relative overflow-hidden px-5 py-2 group rounded-full text-white bg-[#1d194e]"
        >
            <a href="/r.pdf" target="_blank">
                <div
                    class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                />
                <h4 class="relative z-9">Resume</h4>
            </a>
        </button>
        <button
            class="blueShadow relative overflow-hidden px-5 py-2 group rounded-full text-white bg-[#1d194e]"
        >
            <a href="mailto:freelancer.jay.mondal@gmail.com" target="_blank"
                ><div
                    class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                />
                <h4 class="relative z-9">Get in touch</h4>
            </a>
        </button>
    </div>
    
</header>