<template>
  <div class="min-h-screen bg-gray-50">
    <nav class="bg-white shadow-sm">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between h-16">
          <div class="flex items-center">
            <NuxtLink to="/" class="text-xl font-bold text-gray-900">Portfolio</NuxtLink>
          </div>
          <div class="flex items-center space-x-8">
            <NuxtLink to="/about" class="text-gray-700 hover:text-gray-900">About</NuxtLink>
            <NuxtLink to="/projects" class="text-gray-700 hover:text-gray-900">Projects</NuxtLink>
            <NuxtLink to="/skills" class="text-gray-700 hover:text-gray-900">Skills</NuxtLink>
            <NuxtLink to="/contact" class="text-gray-700 hover:text-gray-900">Contact</NuxtLink>
          </div>
        </div>
      </div>
    </nav>

    <slot />

    <footer class="bg-gray-800">
      <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:px-8">
        <p class="text-center text-base text-gray-400">
          © {{ new Date().getFullYear() }} Your Name. All rights reserved.
        </p>
      </div>
    </footer>
  </div>
</template>

<script setup>
// Layout logic here
</script>