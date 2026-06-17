<template>
  <header class="bg-slate-900 shadow-lg">
    <div class="container mx-auto px-6 h-20 flex items-center justify-between">
      <div class="flex items-center gap-4">
        <img
          src="/364-3644305_old-school-gym-logo.png"
          alt="Gym Logo"
          width="400"
          height="600"
          class="w-16 h-16 object-contain rounded-full border-2 border-blue-500 bg-white p-1"
        />

        <div>
          <h1 class="text-2xl font-bold text-white tracking-wide">Sport</h1>
          <p class="text-sm text-slate-300">Train. Compete. Elevate.</p>
        </div>
      </div>

      <nav class="hidden md:flex items-center gap-8 text-sm font-medium">
        <NuxtLink to="/" class="text-white hover:text-blue-400 transition duration-300">
          Home
        </NuxtLink>
        <NuxtLink to="/about" class="text-white hover:text-blue-400 transition duration-300">
          About
        </NuxtLink>
        <NuxtLink to="/contact" class="text-white hover:text-blue-400 transition duration-300">
          Contact
        </NuxtLink>
      </nav>
    </div>
  </header>
</template>