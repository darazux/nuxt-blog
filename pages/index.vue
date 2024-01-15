<!-- index.vue -->

<template>
  <div>
    <div class="hero">
      <nuxt-img src="/images/index-hero.jpg" alt="hero" format="webp" />
      <div class="textContainer">
        <h1>I'm darazux</h1>
        <h3>JavaScript Developer</h3>
      </div>
    </div>
    <div class="container">
      <div class="profile">
        <div>
          <h2>JavaScript Nerd</h2>
          <p></p>
        </div>
        <nuxt-img src="/images/profile.jpg" alt="profile" format="webp" />
      </div>
      <div class="skills">
        <h2>Skills</h2>
        <div class="skillsContainer">
          <div>
            <img src="/images/javascript.svg" alt="javascript" /><span
              >JavaScript / 3 years</span
            >
          </div>
          <div>
            <img src="/images/react.svg" alt="react" />
            <span>React / 0.5 years</span>
          </div>
          <div>
            <img src="/images/vue.svg" alt="vue" />
            <span>Vue / 0.5 years</span>
          </div>
          <div>
            <img src="/images/nuxt.svg" alt="nuxt" />
            <span>Nuxt / 0.5 years</span>
          </div>
        </div>
      </div>
      <div class="ctaButton">
        <NuxtLink to="/contact">Make It Happen!</NuxtLink>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: 'darazux officeial site.',
  meta: [{ name: 'description', content: 'darazuxのポートフォリオサイトです' }],
});
</script>
