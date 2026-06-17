<template>
  <main class="bg-slate-950">
    <section class="relative overflow-hidden bg-slate-950 py-20 text-white">
      <div class="absolute inset-0 bg-[radial-gradient(circle_at_top,_rgba(37,99,235,0.18),_transparent_22%),radial-gradient(circle_at_bottom,_rgba(14,165,233,0.1),_transparent_18%)]"></div>
      <div
        class="absolute inset-0 bg-cover bg-center"
        style="background-image: url('/NRG-Gym-Essendon-1.jpg');"
      ></div>
      <div class="absolute inset-0 bg-gradient-to-r from-slate-950 via-slate-950/85 to-slate-950/90"></div>
      <div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/25 to-transparent"></div>
      <div class="relative z-10 container mx-auto grid items-center gap-12 px-6 lg:grid-cols-[1.1fr_0.9fr]">
        <div>
          <p class="text-sm font-semibold uppercase tracking-[0.35em] text-cyan-300">
            Sport
          </p>
          <h1 class="mt-4 text-4xl font-black leading-tight md:text-6xl">
            Train with purpose. <span class="text-cyan-300">Own your power.</span>
          </h1>
          <p class="mt-6 max-w-xl text-lg text-slate-300">
            Discover a high-energy fitness experience built to push your limits,
            sharpen your focus, and keep you moving with confidence.
          </p>

          <div class="mt-8 flex flex-wrap gap-4">
            <NuxtLink
              to="/contact"
              class="rounded-xl bg-cyan-500 px-6 py-3 font-semibold text-slate-950 transition hover:bg-cyan-400"
            >
              Get Started
            </NuxtLink>
            <NuxtLink
              to="/about"
              class="rounded-xl border border-cyan-400/30 bg-white/5 px-6 py-3 font-semibold text-white transition hover:bg-cyan-400/10"
            >
              Learn More
            </NuxtLink>
          </div>
        </div>

        <div class="flex justify-center lg:justify-end">
          <div class="relative w-full max-w-md">
            <div class="absolute inset-0 rounded-3xl bg-cyan-500/15 blur-3xl"></div>
            <img
              src="/364-3644305_old-school-gym-logo.png"
              alt="Fitness hero illustration"
              class="relative w-full rounded-3xl border border-cyan-400/20 bg-slate-900/70 shadow-2xl"
            />
          </div>
        </div>
      </div>
    </section>

    <section class="bg-slate-950 py-16 text-slate-100">
      <div class="container mx-auto px-6">
        <div class="mx-auto max-w-2xl text-center">
          <p class="text-sm font-semibold uppercase tracking-[0.35em] text-cyan-300">
            Why members stay
          </p>
          <h2 class="mt-3 text-3xl font-bold md:text-4xl">
            Everything you need to stay consistent.
          </h2>
          <p class="mt-4 text-lg text-slate-300">
            A balanced mix of coaching, structure, and recovery to keep your routine sharp and motivating.
          </p>
        </div>

        <div class="mt-10 grid gap-6 md:grid-cols-3">
          <div class="overflow-hidden rounded-2xl border border-cyan-400/10 bg-slate-900 shadow-2xl shadow-cyan-950/20">
            <img
              src="/19dd5fe0-7aaa-47cb-90fd-26a364e29107.webp"
              alt="Guided training"
              class="h-52 w-full object-cover"
            />
            <div class="p-6">
              <div class="text-3xl text-cyan-300">🏋️</div>
              <h3 class="mt-4 text-xl font-semibold">Guided training</h3>
              <p class="mt-2 text-slate-300">
                Follow structured programs that adapt to your goals and schedule.
              </p>
            </div>
          </div>
          <div class="overflow-hidden rounded-2xl border border-cyan-400/10 bg-slate-900 shadow-2xl shadow-cyan-950/20">
            <img
              src="/1.jpg"
              alt="Recovery focus"
              class="h-52 w-full object-cover"
            />
            <div class="p-6">
              <div class="text-3xl text-cyan-300">💧</div>
              <h3 class="mt-4 text-xl font-semibold">Recovery focus</h3>
              <p class="mt-2 text-slate-300">
                Build better habits with recovery routines that help you recharge.
              </p>
            </div>
          </div>
          <div class="overflow-hidden rounded-2xl border border-cyan-400/10 bg-slate-900 shadow-2xl shadow-cyan-950/20">
            <img
              src="/download.jpg"
              alt="Clear progress"
              class="h-52 w-full object-cover"
            />
            <div class="p-6">
              <div class="text-3xl text-cyan-300">📈</div>
              <h3 class="mt-4 text-xl font-semibold">Clear progress</h3>
              <p class="mt-2 text-slate-300">
                Track every win and stay motivated with measurable milestones.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-slate-900 py-16 text-white">
      <div class="container mx-auto grid gap-10 px-6 lg:grid-cols-[0.95fr_1.05fr]">
        <div>
          <p class="text-sm font-semibold uppercase tracking-[0.35em] text-cyan-300">
            Program highlights
          </p>
          <h2 class="mt-3 text-3xl font-bold text-white md:text-4xl">
            Designed for beginners and experienced athletes alike.
          </h2>
          <p class="mt-4 text-lg text-slate-300">
            From quick daily sessions to long-term transformation plans, our experience is built to support real life.
          </p>
        </div>

        <div class="grid gap-4">
          <div class="rounded-2xl border border-white/10 bg-slate-950/70 p-5">
            <h3 class="text-lg font-semibold text-white">Flexible routines</h3>
            <p class="mt-2 text-slate-300">
              Mix strength, cardio, and mobility into sessions that fit your routine.
            </p>
          </div>
          <div class="rounded-2xl border border-white/10 bg-slate-950/70 p-5">
            <h3 class="text-lg font-semibold text-white">Community support</h3>
            <p class="mt-2 text-slate-300">
              Stay accountable with encouraging coaching and a motivating environment.
            </p>
          </div>
          <div class="rounded-2xl border border-white/10 bg-slate-950/70 p-5">
            <h3 class="text-lg font-semibold text-white">Expert guidance</h3>
            <p class="mt-2 text-slate-300">
              Learn the right methods, avoid burnout, and build lasting habits.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-slate-950 py-16 text-white">
      <div class="container mx-auto grid gap-8 px-6 lg:grid-cols-[1fr_0.9fr]">
        <div class="rounded-3xl border border-cyan-400/10 bg-gradient-to-br from-slate-900 to-slate-950 p-8 shadow-2xl shadow-cyan-950/20">
          <p class="text-sm font-semibold uppercase tracking-[0.35em] text-cyan-300">
            Member story
          </p>
          <p class="mt-4 text-2xl font-semibold leading-relaxed text-white">
            “I finally feel energized, focused, and proud of the habits I’m building.”
          </p>
          <p class="mt-4 text-slate-300">— Maya, monthly member</p>
        </div>

        <div class="grid gap-4 sm:grid-cols-2">
          <div class="rounded-2xl border border-white/10 bg-slate-900 p-6">
            <p class="text-3xl font-bold text-cyan-300">4.9/5</p>
            <p class="mt-2 text-slate-300">Average member satisfaction</p>
          </div>
          <div class="rounded-2xl border border-white/10 bg-slate-900 p-6">
            <p class="text-3xl font-bold text-cyan-300">20+</p>
            <p class="mt-2 text-slate-300">Weekly sessions and classes</p>
          </div>
          <div class="rounded-2xl border border-white/10 bg-slate-900 p-6 sm:col-span-2">
            <p class="text-3xl font-bold text-cyan-300">100%</p>
            <p class="mt-2 text-slate-300">Commitment to helping you stay motivated</p>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-gradient-to-r from-slate-950 via-slate-900 to-cyan-950 py-16 text-white">
      <div class="container mx-auto px-6 text-center">
        <h2 class="text-3xl font-bold md:text-4xl">Ready to take the next step?</h2>
        <p class="mx-auto mt-4 max-w-2xl text-lg text-slate-300">
          Join today and start building the energy, strength, and confidence you want.
        </p>
        <div class="mt-8 flex justify-center gap-4">
          <NuxtLink
            to="/contact"
            class="rounded-xl bg-cyan-500 px-6 py-3 font-semibold text-slate-950 transition hover:bg-cyan-400"
          >
            Start Now
          </NuxtLink>
          <NuxtLink
            to="/about"
            class="rounded-xl border border-cyan-400/30 bg-white/5 px-6 py-3 font-semibold text-white transition hover:bg-cyan-400/10"
          >
            Explore More
          </NuxtLink>
        </div>
      </div>
    </section>
  </main>
</template>