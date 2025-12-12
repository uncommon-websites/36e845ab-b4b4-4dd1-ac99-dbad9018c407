<script lang="ts">
  import Logo from "./Logo.svelte";
  export let title: string = "Atelier Tech";
</script>

<header class="fixed top-0 left-0 w-full z-50 px-6 py-6 flex justify-between items-start text-white mix-blend-difference">
  <div class="flex items-center gap-3">
    <Logo />
    <div class="text-2xl font-bold tracking-tighter">{title}</div>
  </div>
  <div class="text-right text-xs font-medium leading-tight opacity-90">
    <p>AI-Powered PR Strategy</p>
    <p class="opacity-70">Data Analysis. Technology Integration.</p>
  </div>
</header>
