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
          <p>Developed full-featured clinician application.</p>
        </div>
        <div class="item">
          <i class="ri-restaurant-2-line"></i>
          <a href="#">Recipe Management App</a>
          <p>
            Created a social media application with real-time updates and user
            interactions.
          </p>
        </div>
        <div class="item">
          <i class="ri-news-line"></i>
          <a href="#">Blog Platform</a>
          <p>Built a dynamic blog platform with content management features.</p>
        </div>
        <div class="item">
          <i class="ri-id-card-line"></i>
          <a href="#">Portfolio Website</a>
          <p>
            Designed and built a personal portfolio website to showcase my
            projects and skills.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
