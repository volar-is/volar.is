<script>
  import '$lib/global.css';
  import { fade } from 'svelte/transition';
</script>

<svelte:head>
  <title>Leo Hanney - Volaris</title>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</svelte:head>

<!-- Background animation -->
<div class="absolute inset-0 bg-gradient-to-r from-transparent via-pink-500 to-pink-700 bg-[length:1200%_1200%] animate-gradient-animate z-[-1]" transition:fade={{ duration: 250 }}></div>

<!-- Centered content -->
<div class="flex items-center justify-center min-h-screen px-4 py-8 bg-black bg-opacity-50">
  <div class="text-center max-w-xl w-full">
    <h1 class="text-4xl sm:text-5xl font-bold text-white mb-6" transition:fade={{ duration: 250 }}>Welcome to Volaris</h1>
    <p class="text-base sm:text-lg text-white mb-6 sm:mb-8" transition:fade={{ duration: 250 }}>
      Volaris is an encryption tool designed to prioritize privacy and security. Built using Rust, it offers a modern and efficient solution for securing your data across multiple platforms, including desktops, command-line interfaces (CLI), and mobile devices.
    </p>
    <a href="/about" class="bg-white text-pink-400 font-bold py-3 px-6 rounded-full transition duration-300 hover:bg-pink-400 hover:text-white" transition:fade={{ duration: 250 }}>
      Learn More
    </a>
  </div>
</div>

<!-- Tailwind CSS Custom Animation -->
<style>
  @keyframes gradientAnimation {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }

  .animate-gradient-animate {
    animation: gradientAnimation 15s ease infinite;
  }
</style>
