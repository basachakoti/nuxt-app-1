<template>
  <!-- <main>
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/about">About</NuxtLink>
  </main> -->
  <!-- <nav class="navbar navbar-light bg-light">
    <span class="navbar-brand mb-0 h1"
      ><NuxtLink to="/" class="nav-link">Home</NuxtLink></span
    >
  </nav> -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <NuxtLink to="/" class="nav-link">Home</NuxtLink>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNavAltMarkup"
      aria-controls="navbarNavAltMarkup"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <NuxtLink to="/about-us" class="nav-link">About</NuxtLink>
      </div>
    </div>
  </nav>
</template>