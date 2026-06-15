<template>
  <section class="bg-white py-20">
    <div class="container mx-auto px-6">
      
      <!-- Hero Section -->
      <div class="text-center max-w-4xl mx-auto mb-16">
        <h1 class="text-5xl font-bold text-slate-900 mb-6">
          About Us
        </h1>
        <p class="text-lg text-slate-600 leading-relaxed">
          We are passionate about creating innovative digital solutions that
          help businesses grow, connect with their audiences, and achieve
          lasting success. Our team combines creativity, technology, and
          expertise to deliver exceptional results.
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
            src="c:\Users\DELL\Desktop\gym pic.jpg"
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
            <div class="text-4xl mb-4">🚀</div>
            <h3 class="text-xl font-semibold mb-3">Innovation</h3>
            <p class="text-slate-600">
              We embrace creativity and continuously seek better solutions.
            </p>
          </div>

          <div class="text-center p-6">
            <div class="text-4xl mb-4">🤝</div>
            <h3 class="text-xl font-semibold mb-3">Integrity</h3>
            <p class="text-slate-600">
              We build trust through transparency, honesty, and accountability.
            </p>
          </div>

          <div class="text-center p-6">
            <div class="text-4xl mb-4">⭐</div>
            <h3 class="text-xl font-semibold mb-3">Excellence</h3>
            <p class="text-slate-600">
              We are committed to delivering high-quality work and outstanding
              customer experiences.
            </p>
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