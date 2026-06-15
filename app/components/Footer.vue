<template>
  <footer class="bg-slate-900 text-slate-300 py-6 mt-10">
    <div class="container mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-4">
      <p>© 2026 My Company. All rights reserved.</p>
      <div class="flex gap-4 text-sm">
        <NuxtLink to="/" class="hover:text-white transition">Home</NuxtLink>
        <NuxtLink to="/about" class="hover:text-white transition">About</NuxtLink>
        <NuxtLink to="/contact" class="hover:text-white transition">Contact</NuxtLink>
      </div>
    </div>
  </footer>
</template>