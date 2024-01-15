<!-- footer.vue -->

<template>
  <footer>
    <div>
      <a href="https://www.google.com/"
        ><img src="/images/github.svg" alt="logo"
      /></a>
      <hr />
      <NuxtLink to="/blog">Blog</NuxtLink>
      <NuxtLink to="/contact">Contact</NuxtLink>
      <p>©{{ new Date().getFullYear() }} darazux</p>
    </div>
  </footer>
</template>
