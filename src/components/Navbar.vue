<template>
  <div id="nav-bar">
    <header class="d-flex flex-wrap justify-content-center py-3 mb-4">
      <a
        href="/"
        class="
          d-flex
          align-items-center
          mb-3 mb-md-0
          me-md-auto
          text-dark text-decoration-none
        "
      >
        <svg class="bi me-2" width="40" height="32">
          <use xlink:href="#bootstrap" />
        </svg>
        <span class="fs-4 my-title">Lugar</span>
      </a>

      <ul class="nav nav-pills">
        <li class="nav-item"><a href="#" class="nav-link">Home</a></li>
        <li class="nav-item"><a href="#" class="nav-link">About</a></li>
        <li class="nav-item"><a href="#" class="nav-link">Project</a></li>
        <li class="nav-item"><a href="#" class="nav-link">Contact</a></li>
      </ul>
    </header>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
</style>