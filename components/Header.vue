<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <NuxtLink to="/" class="nav-link">
      <img src="~/assets/images/sarvadharma.png" alt="sarvadharma" />
    </NuxtLink>
    <p class="h1">Sri Sadguru Sai Shankar</p>
    <div>
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
          <NuxtLink to="/bhajans" class="nav-link">Bhajans</NuxtLink>
          <NuxtLink to="/stories" class="nav-link">Stories</NuxtLink>
          <NuxtLink to="/quotes" class="nav-link">Quotes</NuxtLink>
        </div>
      </div>
    </div>
  </nav>
</template>
<style lang="scss" scoped>
img {
  width: 150px;
}
</style>