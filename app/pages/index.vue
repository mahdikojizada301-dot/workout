<template>
  <main>
    <section class="bg-gradient-to-br from-slate-950 via-slate-900 to-blue-950 py-16 text-white">
      <div class="container mx-auto grid items-center gap-10 px-6 lg:grid-cols-[1.1fr_0.9fr]">
        <div>
          <p class="text-sm font-semibold uppercase tracking-[0.3em] text-blue-300">
            Build stronger tomorrow
          </p>
          <h1 class="mt-4 text-4xl font-bold leading-tight md:text-6xl">
            Train with purpose. Grow with confidence.
          </h1>
          <p class="mt-6 max-w-xl text-lg text-slate-300">
            Discover a modern fitness experience designed to help you stay focused,
            energized, and motivated every step of the way.
          </p>

          <div class="mt-8 flex flex-wrap gap-4">
            <NuxtLink
              to="/contact"
              class="rounded-lg bg-blue-600 px-6 py-3 font-semibold text-white transition hover:bg-blue-500"
            >
              Get Started
            </NuxtLink>
            <NuxtLink
              to="/about"
              class="rounded-lg border border-white/20 px-6 py-3 font-semibold text-white transition hover:bg-white/10"
            >
              Learn More
            </NuxtLink>
          </div>
        </div>

        <div class="flex justify-center lg:justify-end">
          <img
            src="/364-3644305_old-school-gym-logo.png"
            alt="Fitness hero illustration"
            class="w-full max-w-md rounded-3xl border border-white/10 shadow-2xl"
          />
        </div>
      </div>
    </section>

    <section class="bg-slate-50 py-16 text-slate-800">
      <div class="container mx-auto px-6">
        <div class="mx-auto max-w-2xl text-center">
          <p class="text-sm font-semibold uppercase tracking-[0.3em] text-blue-600">
            Why members stay
          </p>
          <h2 class="mt-3 text-3xl font-bold md:text-4xl">
            Everything you need to stay consistent.
          </h2>
          <p class="mt-4 text-lg text-slate-600">
            A balanced mix of coaching, structure, and recovery tools to keep your routine exciting.
          </p>
        </div>

        <div class="mt-10 grid gap-6 md:grid-cols-3">
          <div class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm">
            <div class="text-3xl">🏋️</div>
            <h3 class="mt-4 text-xl font-semibold">Guided training</h3>
            <p class="mt-2 text-slate-600">
              Follow structured programs that adapt to your goals and schedule.
            </p>
          </div>
          <div class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm">
            <div class="text-3xl">💧</div>
            <h3 class="mt-4 text-xl font-semibold">Recovery focus</h3>
            <p class="mt-2 text-slate-600">
              Build better habits with recovery routines that help you recharge.
            </p>
          </div>
          <div class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm">
            <div class="text-3xl">📈</div>
            <h3 class="mt-4 text-xl font-semibold">Clear progress</h3>
            <p class="mt-2 text-slate-600">
              Track every win and stay motivated with measurable milestones.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-white py-16">
      <div class="container mx-auto grid gap-10 px-6 lg:grid-cols-[0.95fr_1.05fr]">
        <div>
          <p class="text-sm font-semibold uppercase tracking-[0.3em] text-blue-600">
            Program highlights
          </p>
          <h2 class="mt-3 text-3xl font-bold text-slate-900 md:text-4xl">
            Designed for beginners and experienced athletes alike.
          </h2>
          <p class="mt-4 text-lg text-slate-600">
            From quick daily sessions to long-term transformation plans, our experience is built to support real life.
          </p>
        </div>

        <div class="grid gap-4">
          <div class="rounded-2xl border border-slate-200 bg-slate-50 p-5">
            <h3 class="text-lg font-semibold text-slate-900">Flexible routines</h3>
            <p class="mt-2 text-slate-600">
              Mix strength, cardio, and mobility into sessions that fit your routine.
            </p>
          </div>
          <div class="rounded-2xl border border-slate-200 bg-slate-50 p-5">
            <h3 class="text-lg font-semibold text-slate-900">Community support</h3>
            <p class="mt-2 text-slate-600">
              Stay accountable with encouraging coaching and a motivating environment.
            </p>
          </div>
          <div class="rounded-2xl border border-slate-200 bg-slate-50 p-5">
            <h3 class="text-lg font-semibold text-slate-900">Expert guidance</h3>
            <p class="mt-2 text-slate-600">
              Learn the right methods, avoid burnout, and build lasting habits.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-slate-900 py-16 text-white">
      <div class="container mx-auto grid gap-8 px-6 lg:grid-cols-[1fr_0.9fr]">
        <div class="rounded-3xl border border-white/10 bg-white/10 p-8 backdrop-blur">
          <p class="text-sm font-semibold uppercase tracking-[0.3em] text-blue-300">
            Member story
          </p>
          <p class="mt-4 text-2xl font-semibold leading-relaxed">
            “I finally feel energized, focused, and proud of the habits I’m building.”
          </p>
          <p class="mt-4 text-slate-300">— Maya, monthly member</p>
        </div>

        <div class="grid gap-4 sm:grid-cols-2">
          <div class="rounded-2xl border border-white/10 bg-slate-800 p-6">
            <p class="text-3xl font-bold text-blue-300">4.9/5</p>
            <p class="mt-2 text-slate-300">Average member satisfaction</p>
          </div>
          <div class="rounded-2xl border border-white/10 bg-slate-800 p-6">
            <p class="text-3xl font-bold text-blue-300">20+</p>
            <p class="mt-2 text-slate-300">Weekly sessions and classes</p>
          </div>
          <div class="rounded-2xl border border-white/10 bg-slate-800 p-6 sm:col-span-2">
            <p class="text-3xl font-bold text-blue-300">100%</p>
            <p class="mt-2 text-slate-300">Commitment to helping you stay motivated</p>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-green-600 py-16 text-white">
      <div class="container mx-auto px-6 text-center">
        <h2 class="text-3xl font-bold md:text-4xl">Ready to take the next step?</h2>
        <p class="mx-auto mt-4 max-w-2xl text-lg text-green-100">
          Join today and start building the energy, strength, and confidence you want.
        </p>
        <div class="mt-8 flex justify-center gap-4">
          <NuxtLink
            to="/contact"
            class="rounded-lg bg-white px-6 py-3 font-semibold text-green-600 transition hover:bg-slate-100"
          >
            Start Now
          </NuxtLink>
          <NuxtLink
            to="/about"
            class="rounded-lg border border-white/30 px-6 py-3 font-semibold text-white transition hover:bg-white/10"
          >
            Explore More
          </NuxtLink>
        </div>
      </div>
    </section>
  </main>
</template>