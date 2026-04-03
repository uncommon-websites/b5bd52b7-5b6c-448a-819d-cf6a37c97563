<script lang="ts">
  import { onMount } from 'svelte';
</script>

<section class="relative bg-dark-green text-white pt-20 pb-0 overflow-hidden min-h-[110vh]">
  <!-- Main Heading -->
  <div class="container mx-auto px-6 mb-16 relative z-10">
    <h1 class="text-[5rem] md:text-[6rem] lg:text-[7.5rem] leading-[0.9] font-serif text-center max-w-7xl mx-auto font-light tracking-tight">
      Everyday <span class="italic font-normal">Expertise</span> — Digital<br>
      Minds Always On for You.
    </h1>
  </div>

  <!-- Image Grid -->
  <div class="relative w-full max-w-[1600px] mx-auto h-[900px]">
    <!-- Top Left Image -->
    <div class="absolute left-[5%] top-0 w-[22%] h-[450px] overflow-hidden">
       <img src="https://images.unsplash.com/photo-1558904541-efa843a96f01?q=80&w=2000&auto=format&fit=crop" alt="Expert knowledge visualization" class="w-full h-full object-cover opacity-70 hover:opacity-100 transition-opacity duration-500" />
    </div>

    <!-- Center Text (featured work) -->
    <div class="absolute left-[32%] top-12 text-[10px] uppercase tracking-widest border-b border-white/30 pb-1 font-medium text-lime-green/80">
      (Featured Minds)
    </div>

    <!-- Center Right Text -->
    <div class="absolute left-[45%] top-12 max-w-[200px] text-sm font-light leading-relaxed opacity-80">
      Scaling Human Intelligence Through Interactive AI Digital Minds.
    </div>

    <!-- Right Image -->
    <div class="absolute right-[8%] top-[120px] w-[30%] h-[550px] overflow-hidden bg-gray-800">
      <img src="https://images.unsplash.com/photo-1628744448840-55bdb2497bd4?q=80&w=2000&auto=format&fit=crop" alt="AI-powered mentorship platform" class="w-full h-full object-cover opacity-70 hover:opacity-100 transition-opacity duration-500" />
    </div>

    <!-- Bottom Center Image -->
    <div class="absolute left-[25%] bottom-[100px] w-[35%] h-[400px] overflow-hidden z-10 bg-gray-700 shadow-2xl">
      <img src="https://images.unsplash.com/photo-1598902108854-10e335adac99?q=80&w=2000&auto=format&fit=crop" alt="Creator building a digital clone" class="w-full h-full object-cover opacity-80 hover:opacity-100 transition-opacity duration-500" />
    </div>
    
    <!-- CTA Circle -->
    <div class="absolute right-[15%] bottom-[250px] flex flex-col items-end z-20">
      <p class="text-4xl font-serif italic mb-6 leading-[1.1] text-right w-full">
        Ready<br>
        to <span class="italic">Explore</span><br>
        Digital<br>
        Minds?
      </p>
      <a href="/projects" class="w-16 h-16 rounded-full border border-white/30 flex items-center justify-center hover:bg-white hover:text-dark-green transition-all duration-300 group mt-2">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="rotate-45 group-hover:stroke-dark-green transition-colors">
          <path d="M7 17L17 7M17 7H7M17 7V17" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </a>
    </div>
  </div>

  <!-- Big Text Overlay at Bottom -->
  <div class="absolute bottom-[-2vw] left-0 w-full overflow-hidden leading-none select-none pointer-events-none opacity-[0.15] mix-blend-overlay">
    <span class="text-[24vw] font-bold text-lime-green whitespace-nowrap tracking-tighter block text-center transform translate-y-[35%]">
      Delphi.ai
    </span>
  </div>
</section>
