<script>
    import Step from './Step.svelte';
    let steps = [
        {name: 'Smoljames Store', icon: 'fa-solid fa-cart-shopping'},
        {name: 'Ultimate Todos', icon: 'fa-solid fa-list-check'},
        {name: 'Poke', icon: 'fa-solid fa-diagram-project'},
    ];
</script>
<main>

<section id="introPage" class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14">

    <div class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10">
        
        <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl lg:text-7xl">
            
        Hi! I'm <span class="poppins text-violet-400">Zacc </span> Elliott <br/> Full Stack
        
        <span class="poppins text-violet-400">Developer </span> & <span class="poppins text-violet-400">Designer</span>
    
    </h2>
        <p class="text-base sm:text-lg md:text-xl lg:text-2xl">

            My <span class="text-violet-400">favorite tech </span>includes JavaScript (NEXT.JS or SvelteKit), Tailwind CSS, Node.js + Express.js and PostgreSQL or Firebase/Firestore!

        </p>

        <a 
            href="https://www.linkedin.com/in/zacchaeuselliott/"
            class="blueShadow mx-auto lg:mr-auto text-base sm:text-lg md:text-xl poppins 
            relative overflow-hidden px-6 py-3 group rounded-full bg-white
            text-slate-950 cursor-pointer">
           
            <div 
                class="absolute top-0 right-full h-full bg-violet-400 opacity-20 
                group-hover:translate-x-full z-0 duration-200"/>
               
                <h4 class="relative z-9">Get in Touch &rarr;</h4>
            
         </a>
    
    </div>
    <div class="relative shadow-xl grid place-items-center">
        <img src={"img/facemob.png"} alt="profileImage" class="object-cover z-[-2] max-h-[30vh]"/>
    </div>

</section>
<section id="projects" class="py-20 lg:py-32 flex flex-col gap-2 text-center">

<div class="flex flex-col gap-2 text-center">

    <h6 class="text-large sm:text-xl md:text-2xl lg:text-3xl">
        A few of my creative endeavours.
    </h6>
    <h3 class="font-semibold text-4xl sm:text-4xl md:text-5xl lg:text-6xl">
        Curious to <span class="poppins text-violet-400">see</span> my work?
    </h3>
    <a href="https://github.com/AdminZacc"
    target="_blank" class="mx-auto px-4 py-2 rounded-md border border-solid border-white flex item-center gap-2 -mb-4 sm:-mb-0 -mt-10 hover:border-violet-700 duration-200"
    >
    <i class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10"/>
    <Step step={steps[0]}>



    </Step>
    <Step step={steps[1]}>



    </Step>

    <Step step={steps[2]}>


    </Step>

</a>

</div>

</section>




</main>