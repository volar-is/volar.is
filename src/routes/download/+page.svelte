<script>
  import { fade } from 'svelte/transition';
  import '$lib/global.css';
</script>
  
<svelte:head>
  <title>Leo Hanney - Volaris</title>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</svelte:head>

<div class="min-h-screen flex items-center justify-center bg-gray-900 text-white">
  <div class="py-8 bg-gray-800 rounded-lg shadow-lg p-10 text-center hover:shadow-xl transition duration-300" transition:fade={{ duration: 250 }}>
    <h1 class="text-4xl font-bold mb-8" transition:fade={{ duration: 250 }}>Download Volaris</h1>
    <div class="max-w-3xl mx-auto">
      <p class="text-lg mb-6" transition:fade={{ duration: 250 }}>
        Download the latest version of Volaris to ensure your data is secure across all your devices. Choose the appropriate version for your platform.
      </p>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
        <div class="p-6 bg-gray-700 rounded-lg shadow-md flex flex-col justify-between">
          <div>
            <h2 class="text-2xl font-bold mb-4" transition:fade={{ duration: 250 }}>Desktop Version</h2>
            <p class="text-lg mb-4" transition:fade={{ duration: 250 }}>Secure your data on your desktop with our robust and efficient encryption tool.</p>
          </div>
          <p class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-accent hover:text-gray-900 mr-4 cursor-not-allowed grayscale relative group">
          <span class="group-hover:hidden">Download for Desktop</span>
          <span class="hidden group-hover:inline">Coming Soon</span>
          </p>
        </div>
        <div class="p-6 bg-gray-700 rounded-lg shadow-md flex flex-col justify-between">
          <div>
            <h2 class="text-2xl font-bold mb-4" transition:fade={{ duration: 250 }}>CLI Version</h2>
            <p class="text-lg mb-4" transition:fade={{ duration: 250 }}>Use our command-line interface for powerful and flexible encryption operations.</p>
          </div>
          <a href="/download/cli" class="bg-pink-accent text-white font-bold py-2 px-4 rounded-full transition duration-300 hover:bg-pink-500" transition:fade={{ duration: 250 }}>Download for CLI</a>
        </div>
        <div class="p-6 bg-gray-700 rounded-lg shadow-md flex flex-col justify-between">
          <div>
            <h2 class="text-2xl font-bold mb-4" transition:fade={{ duration: 250 }}>Mobile Version</h2>
            <p class="text-lg mb-4" transition:fade={{ duration: 250 }}>Encrypt your data on-the-go with our mobile application.</p>
          </div>
          <p class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-accent hover:text-gray-900 mr-4 cursor-not-allowed grayscale relative group">
          <span class="group-hover:hidden">Download for Mobile</span>
          <span class="hidden group-hover:inline">Coming Soon</span>
          </p>
        </div>
        <div class="p-6 bg-gray-700 rounded-lg shadow-md flex flex-col justify-between">
          <div>
            <h2 class="text-2xl font-bold mb-4" transition:fade={{ duration: 250 }}>Documentation</h2>
            <p class="text-lg mb-4" transition:fade={{ duration: 250 }}>Read our comprehensive documentation to get started with Volaris.</p>
          </div>
          <p class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-accent hover:text-gray-900 mr-4 cursor-not-allowed grayscale relative group">
          <span class="group-hover:hidden">View Documentation</span>
          <span class="hidden group-hover:inline">Coming Soon</span>
          </p>
        </div>
      </div>
      <div class="text-lg" transition:fade={{ duration: 250 }}>
        <a href="/about" class="text-pink-accent font-bold hover:underline transition duration-300">Return to about</a>
      </div>
    </div>
  </div>
</div>
  
