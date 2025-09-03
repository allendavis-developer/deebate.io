<!DOCTYPE html>
<html lang="en" data-theme="light">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Debate Live</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;700;800&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdn.jsdelivr.net/npm/daisyui@4.12.10/dist/full.min.css" rel="stylesheet" type="text/css" />
</head>
<body>
  <div class="min-h-screen bg-base-100 flex flex-col justify-center transition-colors duration-300" style="font-family: 'Inter', sans-serif;">
    <!-- Dark Mode Toggle -->
    <div class="fixed top-4 right-4 z-50">
      <label class="swap swap-rotate btn btn-circle btn-ghost">
        <input type="checkbox" class="theme-controller" value="dark" />
        <!-- sun icon -->
        <svg class="swap-off fill-current w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
          <path d="M5.64,17l-.71.71a1,1,0,0,0,0,1.41,1,1,0,0,0,1.41,0l.71-.71A1,1,0,0,0,5.64,17ZM5,12a1,1,0,0,0-1-1H3a1,1,0,0,0,0,2H4A1,1,0,0,0,5,12Zm7-7a1,1,0,0,0,1-1V3a1,1,0,0,0-2,0V4A1,1,0,0,0,12,5ZM5.64,7.05a1,1,0,0,0,.7.29,1,1,0,0,0,.71-.29,1,1,0,0,0,0-1.41l-.71-.71A1,1,0,0,0,4.93,6.34Zm12,.29a1,1,0,0,0,.7-.29l.71-.71a1,1,0,1,0-1.41-1.41L17,5.64a1,1,0,0,0,0,1.41A1,1,0,0,0,17.66,7.34ZM21,11H20a1,1,0,0,0,0,2h1a1,1,0,0,0,0-2Zm-9,8a1,1,0,0,0-1,1v1a1,1,0,0,0,2,0V20A1,1,0,0,0,12,19ZM18.36,17A1,1,0,0,0,17,18.36l.71.71a1,1,0,0,0,1.41,0,1,1,0,0,0,0-1.41ZM12,6.5A5.5,5.5,0,1,0,17.5,12,5.51,5.51,0,0,0,12,6.5Zm0,9A3.5,3.5,0,1,1,15.5,12,3.5,3.5,0,0,1,12,15.5Z"/>
        </svg>
        <!-- moon icon -->
        <svg class="swap-on fill-current w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
          <path d="M21.64,13a1,1,0,0,0-1.05-.14,8.05,8.05,0,0,1-3.37.73A8.15,8.15,0,0,1,9.08,5.49a8.59,8.59,0,0,1,.25-2A1,1,0,0,0,8,2.36,10.14,10.14,0,1,0,22,14.05,1,1,0,0,0,21.64,13Zm-9.5,6.69A8.14,8.14,0,0,1,7.08,5.22v.27A10.15,10.15,0,0,0,17.22,15.63a9.79,9.79,0,0,0,2.1-.22A8.11,8.11,0,0,1,12.14,19.73Z"/>
        </svg>
      </label>
    </div>

    <div class="hero py-4 bg-base-100 transition-colors duration-300">
      <div class="hero-content flex flex-col lg:flex-row lg:justify-between items-center w-full max-w-6xl mx-auto px-8">
        <div class="flex-1 text-center lg:text-left mb-8 lg:mb-0">
          <h1 class="text-4xl md:text-6xl lg:text-7xl font-bold text-base-content leading-tight">
            Jump in, pick a side, and debate live!
          </h1>
        </div>
        <div class="flex-shrink-0 lg:ml-16">
          <button class="font-bold text-white bg-orange-500 hover:bg-orange-600 text-3xl md:text-4xl lg:text-6xl px-8 md:px-10 lg:px-12 py-3 md:py-4 h-auto min-h-[50px] md:min-h-[60px] rounded-2xl border-4 border-orange-500 hover:border-orange-600 transition-all duration-200">
            START NOW!
          </button>
        </div>
      </div>
    </div>
    <div class="py-16 bg-base-100 transition-colors duration-300">
      <div class="max-w-4xl mx-auto px-8">
        <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold text-center text-base-content mb-12" style="text-decoration: underline; text-decoration-thickness: 4px; text-underline-offset: 8px; text-decoration-color: #f97316;">
          How it works
        </h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
          <div class="text-center">
            <div class="text-6xl mb-4">🎯</div>
            <h3 class="text-xl font-bold text-base-content mb-2">Pick your stance</h3>
            <p class="text-base-content">See a debate topic and choose: agree or disagree. You have 20 seconds to decide.</p>
          </div>
          <div class="text-center">
            <div class="text-6xl mb-4">⚡</div>
            <h3 class="text-xl font-bold text-base-content mb-2">Get matched instantly</h3>
            <p class="text-base-content">We pair you with someone who picked the opposite side. No waiting, no browsing profiles.</p>
          </div>
          <div class="text-center">
            <div class="text-6xl mb-4">🎙️</div>
            <h3 class="text-xl font-bold text-base-content mb-2">Debate live</h3>
            <p class="text-base-content">Jump into a voice chat and make your case. Keep it civil, keep it real.</p>
          </div>
          <div class="text-center">
            <div class="text-6xl mb-4">🔄</div>
            <h3 class="text-xl font-bold text-base-content mb-2">Next topic, next opponent</h3>
            <p class="text-base-content">Finished? Hit next and debate someone new on a different topic. It's that simple.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <script>
    (function() {
      // Initialize theme based on user preference or default to light
      const themeController = document.querySelector('.theme-controller');
      const htmlElement = document.documentElement;

      // Check for saved theme preference or default to 'light'
      const currentTheme = localStorage.getItem('theme') || 'light';
      htmlElement.setAttribute('data-theme', currentTheme);
      themeController.checked = currentTheme === 'dark';

      // Listen for theme changes
      themeController.addEventListener('change', function() {
        const newTheme = this.checked ? 'dark' : 'light';
        htmlElement.setAttribute('data-theme', newTheme);
        localStorage.setItem('theme', newTheme);
      });
    })();
  </script>
</body>
</html>
