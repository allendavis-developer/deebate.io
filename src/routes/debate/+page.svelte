<script>
  import { onMount } from 'svelte';

  let prompt = "Abortion should be illegal.";

  let timeLeft = 20;
  let timer;

  onMount(() => {
    timer = setInterval(() => {
      if (timeLeft > 0) {
        timeLeft -= 1;
      } else {
        clearInterval(timer);
      }
    }, 1000);
  });

  function pickSide(side) {
    console.log("User picked:", side);
    clearInterval(timer);
    // Later: navigate to debate room or save choice
  }
</script>

<div 
  class="min-h-screen flex flex-col items-center justify-center bg-base-100 text-center px-6"
  style="font-family: 'Space Mono', monospace;"
>
  <!-- Header -->
  <h1 class="text-5xl md:text-6xl font-bold mb-12">⚖️ Debate Prompt</h1>

  <!-- Debate Statement -->
  <p class="text-3xl md:text-4xl mb-16">"{prompt}"</p>

  <!-- Pick your side -->
  <div class="flex flex-col md:flex-row gap-10 mb-16">
    <button 
      on:click={() => pickSide('agree')}
      class="font-bold text-white bg-green-500 hover:bg-green-600 text-3xl md:text-4xl px-12 md:px-16 py-6 md:py-8 h-auto min-h-[70px] md:min-h-[90px] rounded-2xl border-4 border-green-500 hover:border-green-600 transition-all duration-200"
    >
      👍 AGREE
    </button>
    <button 
      on:click={() => pickSide('disagree')}
      class="font-bold text-white bg-red-500 hover:bg-red-600 text-3xl md:text-4xl px-12 md:px-16 py-6 md:py-8 h-auto min-h-[70px] md:min-h-[90px] rounded-2xl border-4 border-red-500 hover:border-red-600 transition-all duration-200"
    >
      👎 DISAGREE
    </button>
  </div>

  <!-- Countdown -->
  <p class="text-2xl md:text-3xl font-bold">⏳ Time remaining: {timeLeft}s</p>
</div>
