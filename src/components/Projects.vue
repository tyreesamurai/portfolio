<script setup>
function openGitHub() {
  window.open(
    "https://github.com/tyreesamurai?tab=repositories",
    "_blank",
    "noopener,noreferrer",
  );
}
</script>

<template>
  <div class="projects" id="projects">
    <div class="inner">
      <p class="debug"><i class="ri-command-line"></i> Troubleshoot & Debug</p>
      <h2>Projects Showcase</h2>
      <p class="info">
        Take a look at some of my notable projects, showcasing my ability to
        design and develop effective web solutions.
      </p>
      <button @click="openGitHub">
        Explore my projects <i class="ri-arrow-right-line"></i>
      </button>

      <div class="items">
        <div class="item">
          <i class="ri-hospital-line"></i>
          <a
            href="https://github.com/tyreesamurai/vcu-clinician-app"
            target="_blank"
            rel="noopener noreferrer"
            >Clinician App</a
          >
          <p>
            Developed a cross-platform clinician application using React Native
            and Expo, featuring multi-tab navigation, patient data input forms,
            and responsive design for tablet use in medical environments.
          </p>
        </div>
        <div class="item">
          <i class="ri-restaurant-2-line"></i>
          <a
            href="https://github.com/tyreesamurai/recipe-assistant"
            target="_blank"
            rel="noopener noreferrer"
            >Recipe Management App</a
          >
          <p>
            Built a full-stack web app with ASP.NET Core, PostgreSQL, and
            Next.js to enable recipe creation, ingredient tracking, and meal
            planning, featuring dynamic search and user-authenticated data
            persistence.
          </p>
        </div>
        <div class="item">
          <i class="ri-gamepad-line"></i>
          <a
            href="https://github.com/tyreesamurai/s-head"
            target="_blank"
            rel="noopener noreferrer"
            >Multiplayer Card Game</a
          >
          <p>
            Engineered a real-time multiplayer card game using Go and
            WebSockets, implementing custom game logic, match handling, and
            concurrent state management for seamless online play.
          </p>
        </div>
        <div class="item">
          <i class="ri-id-card-line"></i>
          <a href="#">Portfolio Website</a>
          <p>
            Designed and developed this responsive portfolio using Vue.js,
            interactive components, and a modular project showcase.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
