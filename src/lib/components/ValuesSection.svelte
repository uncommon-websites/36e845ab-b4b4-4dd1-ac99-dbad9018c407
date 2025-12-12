<script lang="ts">
  const photos = [
    {
      title: "Continuous Learning",
      desc: "Stay ahead of AI and data trends with ongoing training, conference attendance, and access to cutting-edge tools.",
      img: "/generated/image-data-scientist-explaining-ai-model-resul-1765577883832-7.webp"
    },
    {
      title: "Client Impact",
      desc: "Work directly with PR agencies to solve real challenges and see the immediate impact of your technical solutions.",
      img: "/generated/image-pr-consultant-presenting-data-insights-t-1765577873479-2.webp"
    },
    {
      title: "Flexible Environment",
      desc: "Remote-first culture with flexible hours, allowing you to work where and when you're most productive.",
      img: "/generated/image-team-of-diverse-consultants-collaboratin-1765577879788-5.webp"
    }
  ];
</script>

<section class="py-24 px-6 md:px-12 bg-white">
  <div class="max-w-xl mb-16">
    <h3 class="text-lg font-bold mb-2">We invest in expertise, not perks.</h3>
    <p class="text-gray-500 text-sm leading-relaxed">
      At Atelier Tech, we prioritize professional growth and meaningful work over superficial benefits. Our team members are empowered to become industry experts, working on challenging problems that push the boundaries of AI in PR.
    </p>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
    {#each photos as photo}
      <div>
        <div class="aspect-[3/4] rounded-lg overflow-hidden mb-4 bg-gray-100">
          <img src={photo.img} alt={photo.title} class="w-full h-full object-cover" />
        </div>
        <h4 class="text-xs font-bold mb-1">{photo.title}</h4>
        <p class="text-[10px] text-gray-500 leading-relaxed">{photo.desc}</p>
      </div>
    {/each}
  </div>
</section>
