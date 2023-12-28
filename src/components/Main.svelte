<script>
    import Step from "./Step.svelte";
    

    let benefits = [
        {
            metric: "10x",
            name: "Scientific Computation with Python. | Freecodecamp.com",
            description:
                "I taught myself to code using free online resources and absolutely fell in love with the creativity and problem solving that is involved in developing and engineering innovative new online experiences. Starting of with this course by free code camp.",
            link:"https://www.freecodecamp.org/learn/scientific-computing-with-python/",
        },
        //{name: "a product design & UX finatic",description:"Carefully crafting and designing amazing user experiences allows me to express and experiment with every morsel of creativity I have. I love the challenge of learning new design concepts and enabling users with amazing online experiences.",},
        
    ];
    let benefits1 = [
        //{metric: "10x",name: "Internship at Gogol",description:"I taught myself to code using free online resources and absolutely fell in love with the creativity and problem solving that is involved in developing and engineering innovative new online experiences. Starting of with JavaScript, HTML & CSS and evolving my knowledge base to include JavaScript frameworks, backend programming, design, cloud services and much much more.",link:"https://www.gogol.com/" },
        
    ];
</script>

<main class="flex flex-col flex-1 p-4 m-10">
    <section
        id="introPage"
        class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
    >
        <div
            class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
        >
            <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
                Namaste, I'm <span class=" text-[#48cae4]">Jay Mondal</span>
                <br />
            </h2>
            <h3 class="text-xl sm:text-2xl md:text-3xl">
                AI & Machine Learning Enthusiast.
            </h3>
            <p class="text-base sm:text-lg md:text-xl ">
                I code algorithms out of raw math. <span class="text-[#48cae4]"></span>Mostly I am a pyhton dev, come up with statics and machine learning models using <span class="text-[#48cae4]"> pandas, numpy, scikit-learn, tensorflow, pytorch and other libraries.</span>
            </p>
            <button
                class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-[#023e8a] text-white border-slate-950 hover:bg-slate-950 hover:text-white"
            >
                <div
                    class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                /><a href="mailto:freelancer.jay.mondal@gmail.com"><h4 class="relative z-9">Get in touch &rarr;</h4></a>
                
            </button>
            <button
                class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-9 py-3 group rounded-full bg-[#023e8a] text-white border-slate-950 hover:bg-slate-950 hover:text-white md:hidden"
            >
                <div
                    class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                /><a href="/r.pdf"><h4 class="relative z-9">Resume &rarr;</h4></a>
                
            </button>
        </div>
        <div class="relative shadow-2xl grid place-items-center">
            <img
                src={"profile.jpg"}
                alt="Jay Mondal"
                class="object-cover z-[2] max-h-[70vh]"
            />
        </div>
        <!-- <div  class="flex p-0.5 relative max-w-[700px] w-full mx-auto">
            <div
                class="absolute inset-0 overflow-hidden rounded-md flex items-center justify-center"
            >
                <div
                    class="bg-gradient-to-r absolute inset-[-20px]  from-violet-800 to-indigo-800 specialSpin"
                />
            </div>

            <img
                src={"images/zetane-engine.jpeg"}
                alt="Zetane Engine"
                class="w-full h-full object-cover z-[2]"
            />
        </div> -->
    </section>
    <section class="py-20 lg:py-32 flex flex-col gap-24" id="more intro">
        <div class="flex flex-col gap-2 text-center">
            <h6 class="text-large sm:text-xl md:text-2xl">
                I work with computers because I have an irresistable urge to create.
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                <span class="poppins text-[#48cae4]">About Me</span> and my work.
            </h3>
            <p class="md:p-10 md:mx-20">
                I have started with Machine Learning and Artificial Intelligence because it represents the human conciousness and some of its Intelligence. Currently I am learning basics of AI and Data Science. But to build real world work experiences I am constantly looking to build different projects while learning. So I am open to collaborate on open source projects or anything You can come with .
            </p>
        </div>
        <a
            href="/"
            target="_blank"
            class="mx-auto px-4 py-2 rounded-md border border-solid border-slate-950 flex items-center gap-2 -mb-4 sm:-mb-0 -mt-10 hover:border-violet-700 duration-200"
        >
            <i class="" />
            <p>Download Resume &rarr;</p>
        </a>
    </section>
    <section
        id="education"
        class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
    >
        <!-- <div class="z-[-1] bg-violet-950 w-screen left-1/2 -translate-x-1/2 top-0 h-full absolute"> </div> -->
        <div
            class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-[#03045e] violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-[#03045e]  py-4 "
        >
            <h6 class="text-large sm:text-xl md:text-2xl">
                Educational Background
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                The <span class="poppins text-[#48cae4]">path </span>I took to become a <span class="poppins text-[#48cae4]">Machine Learning </span> Engineer.
            </h3>
        </div>
        <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
            As follows...
        </p>
        <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
            {#each benefits as benefit, index}
                <!-- <div class="flex flex-col gap-2 mx-auto">
                    <div class="flex items-end gap-4">
                        <p
                            class="poppins text-6xl sm:text-7xl md:text-8xl text-slate-500 font-medium"
                        >
                            {benefit.metric}
                        </p>
                        <p
                            class="text-xl sm:text-2xl md:text-3xl capitalize pb-2"
                        >
                            {benefit.name}
                        </p>
                    </div>
                    <p class="text-center italic">- {benefit.description}</p>
                </div> -->
                <div class="flex gap-6 sm:gap-8">
                    <p
                        class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
                    >
                        0{index + 1}
                    </p>
                    <div class="flex flex-col gap-6 sm:gap-8">
                        <h3 class="text-2xl sm:text-3xl md:text-5xl">
                            {benefit.name}
                        </h3>
                        <p>{benefit.description}</p>
                        <div>
                        <a class="bg-[#16253e] text-white p-2 border-r-10" href={benefit.link}>Certificate</a>
                        </div>
                    </div>
                    
                </div>
            {/each}
        </div>
    </section>
    <section
        id="experience"
        class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
    >
        <!-- <div class="z-[-1] bg-violet-950 w-screen left-1/2 -translate-x-1/2 top-0 h-full absolute"> </div> -->
        <div
            class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-[#03045e] after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-[#03045e] py-4"
        >
            <h6 class="text-large sm:text-xl md:text-2xl">
                Job experiences.
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                My<span class="poppins text-violet-400"> career </span>history in <span class="poppins text-violet-400">Technology.</span>
            </h3>
        </div>
        <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
            As follows...
        </p>
        <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
            {#each benefits1 as benefit1, index}
                <!-- <div class="flex flex-col gap-2 mx-auto">
                    <div class="flex items-end gap-4">
                        <p
                            class="poppins text-6xl sm:text-7xl md:text-8xl text-slate-500 font-medium"
                        >
                            {benefit.metric}
                        </p>
                        <p
                            class="text-xl sm:text-2xl md:text-3xl capitalize pb-2"
                        >
                            {benefit.name}
                        </p>
                    </div>
                    <p class="text-center italic">- {benefit.description}</p>
                </div> -->
                <div class="flex gap-6 sm:gap-8">
                    <p
                        class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
                    >
                        0{index + 1}
                    </p>
                    <div class="flex flex-col gap-6 sm:gap-8">
                        <h3 class="text-2xl sm:text-3xl md:text-5xl">
                            {benefit1.name}
                        </h3>
                        <p>{benefit1.description}</p>
                        <div>
                            <a class="bg-black text-white p-2 border-r-10" href={benefit1.link}>Certificate</a>
                            </div>
                    </div>
                </div>
            {/each}
        </div>

    </section>
</main>
