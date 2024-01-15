<!-- [id].vue -->

<template>
  <h1>記事ページ</h1>
  <div>
    <div>
      <nuxt-img :src="data.image" alt="blog-image" format="webp" />
    </div>
    <div>
      <div>
        <h1>{{ data.title }}</h1>
        <p>{{ data.date }}</p>
        <ContentDoc />
      </div>
    </div>
  </div>
</template>

<script setup>
const { data } = await useAsyncData(useRoute().path, () =>
  queryContent(useRoute().path).findOne(),
);
</script>
