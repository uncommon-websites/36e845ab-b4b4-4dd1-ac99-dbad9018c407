<script lang="ts">
  import Logo from "./Logo.svelte";
</script>

<footer class="bg-white px-6 md:px-12 pb-32 pt-12">
  <div class="flex flex-col md:flex-row justify-between items-start mb-24">
    <div class="mb-8 md:mb-0 flex items-center gap-3">
      <Logo />
      <h2 class="text-2xl font-bold tracking-tighter">Atelier Tech</h2>
    </div>

    <div class="grid grid-cols-2 gap-x-12 gap-y-8 text-[10px] uppercase tracking-wide text-gray-500">
      <div class="flex flex-col gap-2">
        <a href="#" class="hover:text-primary-600 transition-colors">LinkedIn</a>
        <a href="#" class="hover:text-primary-600 transition-colors">Twitter</a>
      </div>
      <div class="flex flex-col gap-2">
        <a href="#" class="hover:text-primary-600 transition-colors">Privacy Policy</a>
        <a href="#" class="hover:text-primary-600 transition-colors">Terms of Service</a>
      </div>
      <div class="col-span-2">
        <p>© 2024 Atelier Tech</p>
        <p>All Rights Reserved.</p>
      </div>
    </div>
  </div>

  <div class="text-center md:text-left">
    <h1 class="text-[10vw] leading-none font-bold tracking-tighter text-black text-center">
      AI-POWERED PR STRATEGY.
    </h1>
  </div>
</footer>
