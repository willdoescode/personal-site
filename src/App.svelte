<script lang="ts">
	import Tailwindcss from './Tailwindcss.svelte';
</script>

<Tailwindcss />
<main class="min-h-screen flex bg-gray-800">
  <div class="m-auto">
      <h2 class="
      md:mr-20
      md:mb-2
      md:text-7xl
      text-white
      ">
        <span class="text-green-400">for</span>
       _ <span class="text-yellow-400">in</span>
        <span class="text-red-400">0</span>..<span class="text-red-400">10</span><span class="text-purple-400">:</span>
      </h2>
    <a target="_blank" href="https://github.com/willdoescode">
      <h1 class="
      md:ml-15
      hover:underline
      md:text-8xl
      md:text-center
      font-medium
      text-white"
      >Hi, I'm Will
      </h1>
    </a>
  </div>
</main>

<style>
    @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,500;1,400;1,500&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:ital,wght@0,500;1,500&family=JetBrains+Mono:ital,wght@0,500;1,400;1,500&display=swap');
    h1 {
        font-family: "IBM Plex Sans", monospace;
    }
    h2 {
        font-family: "JetBrains Mono", monospace;
        font-style: italic;
    }
</style>
