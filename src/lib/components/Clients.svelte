<script lang="ts">
  const clients = [
    { name: "Matthew Hussey", logo: "" },
    { name: "Lenny Rachitsky", logo: "" },
    { name: "Jay Shetty", logo: "" },
    { name: "Brian Halligan", logo: "" }
  ];
</script>

<section class="bg-white text-gray-900 py-24 px-6 md:px-12 border-t border-gray-100">
  <div class="max-w-7xl mx-auto">
    <!-- Top Label -->
    <div class="mb-12 border-b border-gray-200 pb-4">
      <span class="text-xs uppercase tracking-widest font-medium text-gray-500">Featured Digital Minds</span>
    </div>

    <!-- Headline -->
    <h2 class="text-3xl md:text-4xl font-light leading-tight mb-16 max-w-3xl">
      Trusted by the world's leading coaches, experts, and creators — 
      <span class="font-serif italic text-gray-400">explore some of the minds already scaling their knowledge with Delphi.</span>
    </h2>

    <!-- Logos Grid -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-px bg-gray-200 border border-gray-200">
      <!-- Client 1: Matthew Hussey -->
      <div class="bg-white p-16 flex flex-col items-center justify-center aspect-[4/3] hover:bg-gray-50 transition-colors group">
         <div class="h-32 w-32 relative mb-8 grayscale group-hover:grayscale-0 transition-all duration-500">
            <!-- Abstract brain/mind icon -->
            <svg viewBox="0 0 100 120" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-full h-full">
              <path d="M10 10 H90 V60 C90 90 50 110 50 110 C50 110 10 90 10 60 V10 Z" fill="#6366F1" stroke="#4338CA" stroke-width="2"/>
              <path d="M30 40 Q50 20 70 40 Q80 60 50 75 Q20 60 30 40Z" fill="white" opacity="0.3"/>
              <circle cx="50" cy="50" r="10" fill="white" opacity="0.6"/>
            </svg>
         </div>
         <span class="text-xs font-bold uppercase tracking-wider text-gray-900">Matthew Hussey</span>
      </div>

      <!-- Client 2: Lenny Rachitsky -->
      <div class="bg-white p-16 flex flex-col items-center justify-center aspect-[4/3] hover:bg-gray-50 transition-colors group">
         <div class="flex items-center gap-4 mb-8 grayscale group-hover:grayscale-0 transition-all duration-500">
            <!-- Abstract node/network symbol -->
            <svg width="60" height="60" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M30 0L36 24L60 30L36 36L30 60L24 36L0 30L24 24L30 0Z" fill="#0EA5E9"/>
              <circle cx="30" cy="30" r="5" fill="white"/>
            </svg>
            <div class="flex flex-col">
               <span class="text-3xl font-bold tracking-widest uppercase text-gray-900 leading-none">Lennybot</span>
            </div>
         </div>
         <span class="text-xs font-bold uppercase tracking-wider text-gray-900">Lenny Rachitsky</span>
      </div>

      <!-- Client 3: Jay Shetty -->
      <div class="bg-white p-16 flex flex-col items-center justify-center aspect-[4/3] hover:bg-gray-50 transition-colors group">
         <div class="flex items-center gap-3 mb-8 grayscale group-hover:grayscale-0 transition-all duration-500">
            <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
               <path d="M10 10H25V40H10V10Z" fill="black"/>
               <path d="M25 10H40C40 10 40 25 40 40H25V10Z" fill="black"/>
               <path d="M10 10L25 0L40 10" fill="black"/>
            </svg>
            <span class="text-3xl font-light tracking-[0.2em] uppercase text-gray-900">Jay Shetty</span>
         </div>
         <span class="text-xs font-bold uppercase tracking-wider text-gray-900">Author & Podcast Host</span>
      </div>

      <!-- Client 4: Brian Halligan -->
      <div class="bg-white p-16 flex flex-col items-center justify-center aspect-[4/3] hover:bg-gray-50 transition-colors group">
         <div class="flex flex-col items-start mb-8 grayscale group-hover:grayscale-0 transition-all duration-500">
            <div class="flex items-center gap-2">
               <div class="h-8 w-8 bg-[#E65100]"></div>
               <span class="text-4xl font-bold tracking-widest uppercase text-gray-500">Halligan</span>
            </div>
            <span class="text-[10px] uppercase tracking-widest text-gray-400 self-end mt-1 w-full text-right">HubSpot Co-Founder</span>
         </div>
         <span class="text-xs font-bold uppercase tracking-wider text-gray-900">Brian Halligan</span>
      </div>
    </div>
  </div>
</section>
