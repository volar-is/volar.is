<script>
  import { fade } from 'svelte/transition';
  import '$lib/global.css';
</script>
  
<svelte:head>
  <title>Leo Hanney - Volaris</title>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</svelte:head>

<div class="min-h-screen flex items-center justify-center bg-gray-900 text-white px-4">
  <div class="bg-gray-800 rounded-lg shadow-lg p-6 sm:p-10 text-center hover:shadow-xl transition duration-300 max-w-3xl w-full">
    <h1 class="text-4xl font-bold mb-8" transition:fade={{ duration: 250 }}>Download Volaris for Desktop</h1>
    <div class="max-w-3xl mx-auto">
      <p class="text-lg mb-6" transition:fade={{ duration: 250 }}>
        Download the latest version of Volaris for your desktop. Ensure you choose the correct version for your operating system.
      </p>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
        <a href="https://github.com/volar-is/volaris-gui/releases/download/app-v0.4.0/Volaris_0.4.0_aarch64.dmg" class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-500" transition:fade={{ duration: 250 }}>Download for macOS (ARM)</a>
        <a href="https://github.com/volar-is/volaris-gui/releases/download/app-v0.4.0/Volaris_0.4.0_x64.dmg" class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-500" transition:fade={{ duration: 250 }}>Download for macOS (Intel)</a>
        <a href="https://github.com/volar-is/volaris-gui/releases/download/app-v0.2.0/Volaris_0.4.0_amd64.AppImage" class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-500" transition:fade={{ duration: 250 }}>Download for Linux (AppImage)</a>
        <a href="https://github.com/volar-is/volaris-gui/releases/download/app-v0.4.0/Volaris_0.4.0_amd64.deb" class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-500" transition:fade={{ duration: 250 }}> Download for Linux (Debian)</a> 
        <a href="https://github.com/volar-is/volaris-gui/releases/download/app-v0.4.0/Volaris_0.4.0_x64_en-US.msi" class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-500" transition:fade={{ duration: 250 }}> Download for Windows (MSI)</a>
        <a href="https://github.com/volar-is/volaris-gui/releases/download/app-v0.4.0/Volaris_0.4.0_x64-setup.exe" class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-500" transition:fade={{ duration: 250 }}> Download for Linux (EXE)</a>  
        <a href="/download" class="text-pink-accent font-bold hover:underline transition duration-300">Back to Downloads</a>
      </div>
    </div>
  </div>
</div>