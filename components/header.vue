<!-- header.vue -->

<template>
  <header>
    <div>
      <div>
        <NuxtLink to="/">
          <nuxt-img src="/images/log.png" alt="logo" format="webp" />
        </NuxtLink>
        <ul>
          <li><NuxtLink to="/blog">Blog</NuxtLink></li>
          <li><NuxtLink to="/contact">Contact</NuxtLink></li>
        </ul>
      </div>
    </div>
  </header>
</template>
