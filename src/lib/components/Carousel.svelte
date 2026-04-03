<script lang="ts">
  const projects = [
    {
      id: "01",
      title: "Coaches & Consultants",
      description: "Turn your expertise into a Digital Mind that answers client questions, delivers your frameworks, and scales your impact — 24/7, without cloning your calendar.",
      image: "/generated/image-a-confident-executive-coach-in-a-modern--1775231444316-0.webp"
    },
    {
      id: "02",
      title: "Creators & Thought Leaders",
      description: "Let your audience go deeper than a podcast or newsletter ever could. Your Digital Mind engages fans personally, in your voice, across every channel.",
      image: "https://images.unsplash.com/photo-1497366216548-37526070297c?q=80&w=1000&auto=format&fit=crop"
    },
    {
      id: "03",
      title: "Enterprises & Public Figures",
      description: "From celebrity knowledge vaults to corporate training, Delphi's Immortal tier delivers white-glove setup and unlimited scale for the world's most influential minds.",
      image: "https://images.unsplash.com/photo-1562664348-2182b3712081?q=80&w=1000&auto=format&fit=crop"
    }
  ];
</script>

<section class="bg-dark-green text-white py-24 px-6 md:px-12 overflow-hidden">
  <div class="max-w-7xl mx-auto">
    <!-- Top Label -->
    <div class="mb-12 border-b border-white/10 pb-4">
      <span class="text-xs uppercase tracking-widest font-medium opacity-60">Built for Every Expert, Creator, and Leader</span>
    </div>

    <!-- Header & Nav -->
    <div class="flex flex-col md:flex-row justify-between items-end mb-20 gap-8">
      <h2 class="text-4xl md:text-5xl font-light leading-tight max-w-3xl">
        Serve a <span class="font-serif italic text-lime-green">wide range of experts, coaches, and creators</span>,
        tailored to every audience, platform, and scale — from solo consultants to global public figures.
      </h2>
      
      <div class="flex gap-4">
        <button class="w-12 h-12 rounded-full border border-white/20 flex items-center justify-center hover:bg-white hover:text-dark-green transition-colors">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M19 12H5M5 12L12 19M5 12L12 5" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </button>
        <button class="w-12 h-12 rounded-full border border-white/20 flex items-center justify-center hover:bg-white hover:text-dark-green transition-colors">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M5 12H19M19 12L12 5M19 12L12 19" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </button>
      </div>
    </div>

    <!-- Carousel -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      {#each projects as project}
        <div class="group relative aspect-[4/5] bg-gray-800 overflow-hidden cursor-pointer">
          <img src={project.image} alt={project.title} class="w-full h-full object-cover opacity-60 group-hover:opacity-40 group-hover:scale-105 transition-all duration-700" />
          
          <div class="absolute inset-0 p-8 flex flex-col justify-between">
            <span class="text-xs font-mono opacity-60">({project.id})</span>
            
            <div class="transform translate-y-4 group-hover:translate-y-0 transition-transform duration-500">
              <h3 class="text-2xl font-light mb-4">{project.title}</h3>
              <p class="text-sm opacity-0 group-hover:opacity-80 transition-opacity duration-500 delay-100 font-light leading-relaxed">
                {project.description}
              </p>
            </div>
          </div>
        </div>
      {/each}
    </div>

  </div>
</section>
