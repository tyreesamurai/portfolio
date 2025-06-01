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
        <h2>Hi, I'm Tyree, a Full-Stack Developer</h2>
        <p>
          I'm a curious and capable developer with a strong foundation in both
          frontend and backend technologies. I recently graduated with a degree
          in Computer Science with a concentration in Software Engineering from
          Virginia Commonwealth University, and I’ve been focused on building
          clean, intuitive applications that solve real problems and help me
          grow as a creator.
        </p>
        <p>
          I learn by building. Whether it’s a personal project, a collaborative
          tool, or a new experiment, I’m always exploring ways to sharpen my
          skills and bring creative ideas to life. I care deeply about
          thoughtful design, maintainable code, and delivering experiences that
          feel smooth, useful, and enjoyable to real people.
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
