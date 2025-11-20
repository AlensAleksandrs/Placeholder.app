<script setup>
const domain = window.location.hostname
document.title = `${domain} — Under Construction`
</script>

<template>
  <main class="min-h-screen w-full flex items-center justify-center bg-neutral-900 px-6">
    <section
      class="w-full max-w-sm text-center flex flex-col items-center gap-6"
      aria-labelledby="site-title"
    >
      <img
        src="/src/assets/logo.png"
        alt="Rendezvous logo"
        class="w-3/4 h-auto opacity-90"
        loading="lazy"
      />

      <header>
        <h1
          id="site-title"
          class="text-neutral-200 text-3xl font-serif tracking-wide"
        >
          {{ domain }}
        </h1>

        <h2
          class="text-neutral-300 text-base font-light font-serif mt-2"
        >
          Project currently under development
        </h2>
      </header>

      <p
        class="text-neutral-400 text-sm font-light font-serif leading-relaxed"
      >
        This domain ({{ domain }}) belongs to a SIA Rendezvous project that
        is currently under development. Please return at a later time to check whether
        the site has become available.
      </p>
    </section>
  </main>
</template>
