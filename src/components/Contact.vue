<script setup>
const resumeLink = import.meta.env.BASE_URL + "/resume.pdf";

function openResume() {
  window.open(resumeLink, "_blank", "noopener,noreferrer");
}

function openEmail() {
  window.location.href = "mailto:tyree.fullstack@gmail.com";
}
</script>

<template>
  <div class="contact" id="contact">
    <h2>Interested in Working Together?</h2>
    <div class="items">
      <div class="item">
        <a
          href="mailto:tyree.fullstack@gmail.com"
          target="_blank"
          rel="noopener noreferrer"
          >Schedule a call</a
        >
        <p>Let's discuss your project ideas and how I can help you.</p>
        <button @click="openEmail">Schedule a Call</button>
      </div>
      <div class="item">
        <a :href="resumeLink" target="_blank" rel="noopener noreferrer"
          >Review My Background</a
        >
        <p>
          View my resume to explore the skills, experience, and projects that
          have shaped my journey so far.
        </p>
        <button @click="openResume">Open My Resume</button>
      </div>
    </div>
  </div>
</template>
