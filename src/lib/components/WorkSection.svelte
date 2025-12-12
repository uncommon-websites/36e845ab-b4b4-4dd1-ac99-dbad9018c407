<script lang="ts">
  const projects = [
    {
      client: "Global Tech Launch",
      desc: "AI-powered sentiment analysis driving 340% increase in media coverage.",
      bg: "bg-black",
      img: "/generated/image-close-up-of-analytics-dashboard-showing--1765577871369-1.webp",
      dark: true
    },
    {
      client: "Healthcare PR Firm",
      desc: "Predictive analytics platform reducing campaign planning time by 60%.",
      bg: "bg-gray-100",
      img: "/generated/image-pr-consultant-presenting-data-insights-t-1765577873479-2.webp",
      dark: false
    },
    {
      client: "Consumer Brand Agency",
      desc: "Real-time media monitoring system tracking 50K+ mentions daily.",
      bg: "bg-gray-900",
      img: "/generated/image-real-time-media-monitoring-dashboard-wit-1765577875499-3.webp",
      dark: true
    },
    {
      client: "Financial Services PR",
      desc: "Data integration platform unifying 12 analytics tools into one dashboard.",
      bg: "bg-gray-200",
      img: "/generated/image-financial-data-visualization-with-charts-1765577877591-4.webp",
      dark: false
    },
    {
      client: "Crisis Management Suite",
      desc: "AI early warning system detecting potential issues 48 hours in advance.",
      bg: "bg-[#1a1a1a]",
      img: "/generated/image-close-up-of-analytics-dashboard-showing--1765577871369-1.webp",
      dark: true,
      full: true
    },
    {
      client: "Influencer Campaign",
      desc: "Machine learning model optimizing influencer selection with 85% accuracy.",
      bg: "bg-gray-100",
      img: "/generated/image-real-time-media-monitoring-dashboard-wit-1765577875499-3.webp",
      dark: false
    },
    {
      client: "Media Relations Platform",
      desc: "Automated journalist matching system increasing pitch response rates by 3x.",
      bg: "bg-gray-200",
      img: "/generated/image-financial-data-visualization-with-charts-1765577877591-4.webp",
      dark: false
    }
  ];
</script>

<section class="px-6 md:px-12 py-24 bg-white">
  <div class="max-w-3xl mb-16">
    <h2 class="text-2xl md:text-3xl font-medium leading-tight">
      <span class="font-bold">We transform PR agencies through AI implementation</span> and data-driven technology, helping you deliver campaigns that are measurable, scalable, and impactful.
    </h2>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-2 gap-x-6 gap-y-12">
    {#each projects as project}
      <div class="group cursor-pointer {project.full ? 'md:col-span-2' : ''}">
        <div class={`aspect-[4/3] w-full rounded-lg overflow-hidden relative ${project.bg} mb-4 ${project.full ? 'md:aspect-[2.5/1]' : ''}`}>
          {#if project.img}
             <img src={project.img} alt={project.client} class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" />
          {:else}
             <!-- Placeholder for logos on solid bg -->
             <div class="w-full h-full flex items-center justify-center">
                <span class={`text-2xl font-bold ${project.dark ? 'text-white' : 'text-black'}`}>{project.client} Logo</span>
             </div>
          {/if}
        </div>
        <h3 class="text-sm font-bold mb-1">{project.client}</h3>
        <p class="text-sm text-gray-600">{project.desc}</p>
      </div>
    {/each}
  </div>
</section>
