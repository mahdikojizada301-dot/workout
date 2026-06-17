<template>
  <section class="bg-slate-950 min-h-screen py-20">
    <div class="container mx-auto px-6">

      <!-- Hero -->
      <div class="text-center max-w-4xl mx-auto mb-20">
        <span
          class="inline-block px-4 py-2 bg-blue-500/10 text-blue-400 rounded-full text-sm font-medium mb-6"
        >
          Contact Us
        </span>

        <h1 class="text-5xl md:text-6xl font-bold text-white mb-6">
          Contact <span class="text-blue-500">Sport</span>
        </h1>

        <p class="text-slate-400 text-lg leading-relaxed">
          Have a question, project idea, partnership opportunity, or just want
          to say hello? We'd love to hear from you.
        </p>
      </div>

      <!-- Contact Grid -->
      <div class="grid lg:grid-cols-2 gap-10">

        <!-- Left Side -->
        <div class="space-y-6">

          <div
            class="bg-slate-900 border border-slate-800 rounded-3xl p-8 hover:border-blue-500 transition"
          >
            <div
              class="w-14 h-14 rounded-2xl bg-blue-500/10 flex items-center justify-center mb-5"
            >
              📧
            </div>

            <h3 class="text-white text-2xl font-semibold mb-2">
              Email Us
            </h3>

            <p class="text-slate-400 mb-4">
              Reach out anytime and we'll get back to you as soon as possible.
            </p>

            <a
              href="mailto:hello@yourcompany.com"
              class="text-blue-400 hover:text-blue-300"
            >
              hello@yourcompany.com
            </a>
          </div>

          <div
            class="bg-slate-900 border border-slate-800 rounded-3xl p-8 hover:border-blue-500 transition"
          >
            <div
              class="w-14 h-14 rounded-2xl bg-blue-500/10 flex items-center justify-center mb-5"
            >
              📱
            </div>

            <h3 class="text-white text-2xl font-semibold mb-2">
              Call Us
            </h3>

            <p class="text-slate-400 mb-4">
              Speak directly with our team for support or inquiries.
            </p>

            <a
              href="tel:+123456789"
              class="text-blue-400 hover:text-blue-300"
            >
              +123 456 789
            </a>
          </div>

          <div
            class="bg-slate-900 border border-slate-800 rounded-3xl p-8 hover:border-blue-500 transition"
          >
            <div
              class="w-14 h-14 rounded-2xl bg-blue-500/10 flex items-center justify-center mb-5"
            >
              📍
            </div>

            <h3 class="text-white text-2xl font-semibold mb-2">
              Visit Us
            </h3>

            <p class="text-slate-400">
              Your Business Address Here
            </p>
          </div>

        </div>

        <!-- Contact Form -->
        <div
          class="bg-slate-900 border border-slate-800 rounded-3xl p-8"
        >
          <h2 class="text-3xl font-bold text-white mb-8">
            Send a Message
          </h2>

          <form class="space-y-6">

            <div>
              <label class="block text-slate-300 mb-2">
                Full Name
              </label>

              <input
                type="text"
                placeholder="John Doe"
                class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-4 text-white focus:border-blue-500 focus:outline-none"
              />
            </div>

            <div>
              <label class="block text-slate-300 mb-2">
                Email Address
              </label>

              <input
                type="email"
                placeholder="john@example.com"
                class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-4 text-white focus:border-blue-500 focus:outline-none"
              />
            </div>

            <div>
              <label class="block text-slate-300 mb-2">
                Subject
              </label>

              <input
                type="text"
                placeholder="How can we help?"
                class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-4 text-white focus:border-blue-500 focus:outline-none"
              />
            </div>

            <div>
              <label class="block text-slate-300 mb-2">
                Message
              </label>

              <textarea
                rows="6"
                placeholder="Write your message..."
                class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-4 text-white focus:border-blue-500 focus:outline-none resize-none"
              ></textarea>
            </div>

            <button
              type="submit"
              class="w-full bg-blue-600 hover:bg-blue-700 text-white py-4 rounded-xl font-semibold transition"
            >
              Send Message →
            </button>

          </form>
        </div>

      </div>

      <!-- Bottom Banner -->
      <div
        class="mt-20 bg-gradient-to-r from-blue-600 to-cyan-500 rounded-3xl p-10 text-center"
      >
        <h2 class="text-4xl font-bold text-white mb-4">
          Ready to Start?
        </h2>

        <p class="text-white/90 mb-6">
          Let's discuss your next project and bring your ideas to life.
        </p>

        <button
          class="bg-white text-slate-900 px-8 py-4 rounded-xl font-semibold hover:scale-105 transition"
        >
          Schedule a Meeting
        </button>
      </div>

    </div>
  </section>
</template>