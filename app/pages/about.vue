<template>
  <section class="bg-white py-20">
    <div class="container mx-auto px-6">
      
      <!-- Iconic Hero Section -->
      <div class="text-center max-w-4xl mx-auto mb-16">
        <div class="flex items-center justify-center mb-6">
          <div class="w-28 h-28 rounded-full bg-gradient-to-br from-blue-500 to-indigo-600 flex items-center justify-center shadow-lg">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 64 64" class="w-16 h-16 text-white" fill="none" stroke="currentColor" stroke-width="2">
              <rect x="2" y="28" width="60" height="8" rx="2" fill="white" />
              <rect x="6" y="22" width="6" height="20" rx="1" fill="#edf2ff" transform="rotate(-20 6 22)" />
              <rect x="52" y="22" width="6" height="20" rx="1" fill="#edf2ff" transform="rotate(20 52 22)" />
              <path d="M10 32h44" stroke="#1f2937" stroke-width="1.5" />
            </svg>
          </div>
        </div>

        <h1 class="text-5xl font-bold text-slate-900 mb-4">About AFGsports</h1>
        <p class="text-xl text-slate-600 leading-relaxed mb-2">Train. Compete. Excel.</p>
        <p class="text-lg text-slate-600 leading-relaxed">
          AFGsports brings athletic performance, training programs, and community
          together — built by people who love sport and technology.
        </p>
      </div>

      <!-- Company Story -->
      <div class="grid lg:grid-cols-2 gap-12 items-center mb-20">
        <div>
          <h2 class="text-3xl font-bold text-slate-900 mb-6">
            Our Story
          </h2>
          <p class="text-slate-600 mb-4 leading-relaxed">
            Founded with a vision to make technology more accessible and
            impactful, our company has grown into a trusted partner for
            businesses seeking innovative solutions.
          </p>
          <p class="text-slate-600 leading-relaxed">
            From small startups to established organizations, we work closely
            with our clients to understand their goals and transform ideas into
            reality through modern design and technology.
          </p>
        </div>

        <div>
          <img
            src="/my-gym.jpg"
            alt="Our Team"
            class="rounded-2xl shadow-lg w-full h-[400px] object-cover"
          />
        </div>
      </div>

      <!-- Mission & Vision -->
      <div class="grid md:grid-cols-2 gap-8 mb-20">
        <div class="bg-slate-50 p-8 rounded-2xl">
          <h3 class="text-2xl font-bold text-slate-900 mb-4">
            Our Mission
          </h3>
          <p class="text-slate-600">
            To empower businesses and individuals through innovative digital
            solutions, exceptional service, and long-term partnerships.
          </p>
        </div>

        <div class="bg-slate-50 p-8 rounded-2xl">
          <h3 class="text-2xl font-bold text-slate-900 mb-4">
            Our Vision
          </h3>
          <p class="text-slate-600">
            To become a leading force in digital transformation by helping
            organizations unlock their full potential through technology.
          </p>
        </div>
      </div>

      <!-- Values -->
      <div class="mb-20">
        <h2 class="text-3xl font-bold text-center text-slate-900 mb-12">
          Our Core Values
        </h2>

        <div class="grid md:grid-cols-3 gap-8">
          <div class="text-center p-6">
            <div class="text-4xl mb-4">🏋️</div>
            <h3 class="text-xl font-semibold mb-3">Performance</h3>
            <p class="text-slate-600">We focus on measurable athletic progress and results.</p>
          </div>

          <div class="text-center p-6">
            <div class="text-4xl mb-4">🏆</div>
            <h3 class="text-xl font-semibold mb-3">Commitment</h3>
            <p class="text-slate-600">We support athletes and teams with consistency and care.</p>
          </div>

          <div class="text-center p-6">
            <div class="text-4xl mb-4">⚡</div>
            <h3 class="text-xl font-semibold mb-3">Excellence</h3>
            <p class="text-slate-600">We deliver high-quality programs and exceptional experiences.</p>
          </div>
        </div>
      </div>

      <!-- Statistics -->
      <div class="bg-slate-900 text-white rounded-3xl p-10 mb-20">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
          <div>
            <h3 class="text-4xl font-bold">100+</h3>
            <p class="text-slate-300 mt-2">Projects Completed</p>
          </div>

          <div>
            <h3 class="text-4xl font-bold">50+</h3>
            <p class="text-slate-300 mt-2">Happy Clients</p>
          </div>

          <div>
            <h3 class="text-4xl font-bold">5+</h3>
            <p class="text-slate-300 mt-2">Years Experience</p>
          </div>

          <div>
            <h3 class="text-4xl font-bold">24/7</h3>
            <p class="text-slate-300 mt-2">Support</p>
          </div>
        </div>
      </div>

      <!-- CTA -->
      <div class="text-center max-w-3xl mx-auto">
        <h2 class="text-3xl font-bold text-slate-900 mb-4">
          Let's Build Something Amazing Together
        </h2>
        <p class="text-slate-600 mb-8">
          Whether you're looking to start a new project or improve an existing
          one, we're here to help you achieve your goals.
        </p>

        <NuxtLink
          to="/contact"
          class="inline-flex items-center px-8 py-4 bg-slate-900 text-white rounded-xl hover:bg-slate-800 transition"
        >
          Contact Us
        </NuxtLink>
      </div>

    </div>
  </section>
</template>