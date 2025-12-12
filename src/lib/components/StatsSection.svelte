<script lang="ts">
  const stats = [
    {
      label: "$14B Market",
      desc: "The PR consulting market represents a massive opportunity for technology transformation. We're capturing this market by helping agencies overcome their biggest challenge: implementing AI and data analytics without the technical expertise traditionally required.",
      img: "/generated/image-financial-data-visualization-with-charts-1765577877591-4.webp"
    },
    {
      label: "500 Client Target",
      desc: "Our scalable model allows us to serve hundreds of PR agencies simultaneously. Through proven frameworks, standardized implementations, and comprehensive training programs, we're building the infrastructure to transform the entire PR industry.",
      img: "/generated/image-team-of-diverse-consultants-collaboratin-1765577879788-5.webp"
    },
    {
      label: "Industry Conferences",
      desc: "We reach PR agencies where they gather—at industry conferences and events. By showcasing proven client case studies and demonstrating real ROI, we overcome AI implementation fears and build trust through transparent results.",
      img: "/generated/image-pr-professional-confidently-presenting-a-1765577881831-6.webp"
    },
    {
      label: "Proven Results",
      desc: "Our client case studies speak for themselves: 340% increases in media coverage, 60% reductions in campaign planning time, and 3x improvements in pitch response rates. We don't just promise transformation—we deliver it.",
      img: "/generated/image-close-up-of-analytics-dashboard-showing--1765577871369-1.webp"
    }
  ];
</script>

<section class="py-24 px-6 md:px-12 bg-white border-t border-gray-100">
  <div class="mb-16">
    <p class="text-gray-500 max-w-xl">
      The numbers that drive our mission to transform PR strategy through AI-powered data analysis and technology integration.
    </p>
  </div>

  <div class="space-y-16">
    {#each stats as stat}
      <div class="flex flex-col md:flex-row md:items-start justify-between gap-8 border-b border-gray-100 pb-16 last:border-0">
        <h3 class="text-2xl md:text-4xl font-medium w-full md:w-1/3">{stat.label}</h3>
        <div class="w-full md:w-1/3">
           <p class="text-xs leading-relaxed text-gray-500">{stat.desc}</p>
        </div>
        <div class="w-full md:w-1/6 flex justify-end">
           <img src={stat.img} alt={stat.label} class="w-20 h-20 object-cover rounded bg-gray-100" />
        </div>
      </div>
    {/each}
  </div>
</section>
