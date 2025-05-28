<script setup>
function openEmail() {
  window.location.href = "mailto:tyree.fullstack@gmail.com";
}

function openGithub() {
  window.open(
    "https://github.com/tyreesamurai",
    "_blank",
    "noopener,noreferrer",
  );
}

function openLinkedIn() {
  window.open(
    "https://www.linkedin.com/in/tyree-carpenter/",
    "_blank",
    "noopener,noreferrer",
  );
}
</script>

<template>
  <div class="hero">
    <div class="left-section">
      <div class="top">
        <h2>
          Hi, I'm Tyree — a Full-Stack Developer at the start of something great
        </h2>
        <p>
          I'm a curious and capable developer with a strong foundation in both
          frontend and backend technologies. I recently graduated with a degree
          in Computer Science, and I’ve been focused on building clean,
          intuitive applications that solve real problems and help me grow as a
          creator.
        </p>
        <p>
          I believe in learning by doing, so I spend most of my time creating —
          from personal projects and passion tools to collaborative work that
          pushes my skills further. My goal is to keep leveling up while
          delivering thoughtful, well-built experiences that people actually
          enjoy using.
        </p>

        <div class="buttons">
          <button class="doc" @click="openEmail">
            Get in Touch <i class="ri-arrow-right-line"></i>
          </button>
          <button class="git" @click="openGithub">
            <i class="ri-github-fill"></i> My Github
          </button>
          <button class="git" @click="openLinkedIn">
            <i class="ri-linkedin-box-fill"></i> My LinkedIn
          </button>
        </div>
      </div>
    </div>

    <img src="../assets/hero.jpg" />
  </div>
</template>
