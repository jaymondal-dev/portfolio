<script>
    export let y;

    export let tabs = [
        { name: "About me", link: "#about" },
        { name: "Projects ", link: "#projects" },
        { name: "Blog", link: "/blog" },
        // { name: "Contact", link: "" },
        // {name: '', link: ''},
    ];
</script>

<header
    class={"sticky z-[10] top-0 duration-200 px-4 flex items-center  justify-center border-b border-solid md:hidden" +
        (y > 0
            ? " py-4 bg-[#cacbdb] border-slate-500"
            : " py-6 bg-[#cacbdb] border-transparent")}
    
>
    
    <div class=" p-4 flex items-center gap-6 ">
        {#each tabs as tab, index}
            
            <a
                href={tab.link}
                class="text-xl duration-200 hover:text-violet-700 underline"
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
        
    </div>
    
</header>