<script setup>
function openGithub() {
  window.open(
    "https://github.com/tyreesamurai?tab=repositories",
    "_blank",
    "noopener,noreferrer",
  );
}
</script>

<template>
  <nav>
    <div class="logo">
      <a href="#">Tyree Carpenter</a>
    </div>
    <div class="nav-links">
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </div>
    <button @click="openGithub">
      <i class="ri-github-fill"></i> My Projects
    </button>
  </nav>
</template>
