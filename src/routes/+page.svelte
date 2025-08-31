<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;800&display=swap" rel="stylesheet">
</svelte:head>

<div class="min-h-screen bg-[#0b0f19] flex flex-col justify-center" style="font-family: 'Inter', sans-serif;">
  <div class="hero py-20 bg-[#0b0f19]">
    <div class="hero-content flex-row justify-between items-center w-full max-w-6xl">
      <div class="flex-1">
        <h1 class="text-7xl font-bold text-white leading-tight">
          Jump in, pick a side, and debate live!
        </h1>
      </div>
      <div class="flex-shrink-0 ml-16">
        <button class="btn text-white bg-[#ae2012] hover:bg-[#8b1a0e] text-6xl px-12 py-4 h-auto min-h-[60px] rounded-2xl border-4 border-[#ae2012] hover:border-[#8b1a0e]">
          START NOW!
        </button>
      </div>
    </div>
  </div>

  <div class="py-16 bg-[#0b0f19]">
    <div class="max-w-4xl mx-auto px-8">
      <h2 class="text-5xl font-bold text-center text-white mb-12" style="text-decoration: underline; text-decoration-thickness: 4px; text-underline-offset: 8px; text-decoration-color: #ae2012;">
        How it works
      </h2>
      
      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
        <div class="text-center">
          <div class="text-6xl mb-4">🎯</div>
          <h3 class="text-xl font-bold text-white mb-2">Pick your stance</h3>
          <p class="text-gray-300">See a debate topic and choose: agree or disagree. You have 20 seconds to decide.</p>
        </div>
        
        <div class="text-center">
          <div class="text-6xl mb-4">⚡</div>
          <h3 class="text-xl font-bold text-white mb-2">Get matched instantly</h3>
          <p class="text-gray-300">We pair you with someone who picked the opposite side. No waiting, no browsing profiles.</p>
        </div>
        
        <div class="text-center">
          <div class="text-6xl mb-4">🎙️</div>
          <h3 class="text-xl font-bold text-white mb-2">Debate live</h3>
          <p class="text-gray-300">Jump into a voice chat and make your case. Keep it civil, keep it real.</p>
        </div>
        
        <div class="text-center">
          <div class="text-6xl mb-4">🔄</div>
          <h3 class="text-xl font-bold text-white mb-2">Next topic, next opponent</h3>
          <p class="text-gray-300">Finished? Hit next and debate someone new on a different topic. It's that simple.</p>
        </div>
      </div>
    </div>
  </div>
</div>