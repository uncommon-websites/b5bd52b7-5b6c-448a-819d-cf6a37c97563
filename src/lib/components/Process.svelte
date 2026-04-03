<script lang="ts">
  const steps = [
    {
      id: "01",
      title: "Sign Up and Create Your Profile",
      description: "Get started in minutes by creating your Delphi account and telling us about your expertise, audience, and goals."
    },
    {
      id: "02",
      title: "Upload Your Content and Knowledge",
      description: "Feed your Digital Mind with your existing content — videos, podcasts, writings, courses, and more across 40+ supported formats."
    },
    {
      id: "03",
      title: "Train Your Digital Mind",
      description: "Delphi learns your unique voice, frameworks, and insights, building an interactive AI that thinks and responds like you."
    },
    {
      id: "04",
      title: "Customize Your Experience",
      description: "Set your brand colors, custom domain, and interaction preferences so your Digital Mind feels authentically yours."
    },
    {
      id: "05",
      title: "Deploy Across Your Channels",
      description: "Launch your Digital Mind on your website, WhatsApp, SMS, Slack, or via voice — wherever your audience already lives."
    },
    {
      id: "06",
      title: "Grow, Refine, and Scale",
      description: "Use built-in analytics to sharpen responses over time, sync contacts, and monetize your expertise at unlimited scale."
    }
  ];
</script>

<section class="bg-white text-gray-900 py-24 px-6 md:px-12">
  <div class="max-w-7xl mx-auto">
    <!-- Top Label -->
    <div class="flex justify-between items-center mb-12 border-b border-gray-200 pb-4">
      <span class="text-xs uppercase tracking-widest font-medium text-gray-500">Simple and Clear Onboarding Process</span>
      <span class="text-xs uppercase tracking-widest font-medium text-gray-500">(2025)</span>
    </div>

    <!-- Main Headline -->
    <h2 class="text-4xl md:text-5xl font-light leading-tight mb-24 max-w-4xl">
      Building your Digital Mind is an <span class="font-serif italic">empowering journey</span> — and the process 
      from your first upload to a fully deployed clone is structured to be smooth, transparent, and inspiring.
    </h2>

    <div class="grid grid-cols-1 lg:grid-cols-12 gap-16">
      <!-- Sticky Image -->
      <div class="lg:col-span-5 relative hidden lg:block">
        <div class="sticky top-12 h-[600px] w-full bg-gray-100 overflow-hidden">
           <img src="/generated/image-a-team-of-engineers-and-creators-collabo-1775231455198-4.webp" alt="Collaborative team building Delphi Digital Mind" class="w-full h-full object-cover" />
        </div>
      </div>

      <!-- Steps List -->
      <div class="lg:col-span-7 space-y-0">
        {#each steps as step}
          <div class="group border-b border-gray-200 py-12 first:pt-0 flex gap-8 items-start hover:bg-gray-50/50 transition-colors px-4 -mx-4">
            <span class="text-xs font-mono text-gray-400 mt-2">({step.id})</span>
            <div class="flex-1">
              <h3 class="text-2xl font-light mb-4 group-hover:text-dark-green transition-colors">{step.title}</h3>
              <p class="text-gray-500 font-light leading-relaxed max-w-md opacity-0 h-0 overflow-hidden group-hover:opacity-100 group-hover:h-auto transition-all duration-500">
                {step.description}
              </p>
            </div>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
