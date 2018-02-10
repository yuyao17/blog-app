<template>
  <section class="post-list">
      <PostPreview
        id="1"
        thumbnail="https://static.pexels.com/photos/248159/pexels-photo-248159.jpeg"
        title="Hello there!"
        previewText="This is my first post!" />
      <PostPreview
        id="2"
        thumbnail="https://static.pexels.com/photos/248159/pexels-photo-248159.jpeg"
        title="Hello there! - Second time"
        previewText="This is my second post!" />
      <PostPreview
        id="3"
        thumbnail="https://static.pexels.com/photos/248159/pexels-photo-248159.jpeg"
        title="Hello there! - Third time"
        previewText="This is my third post!" />
    </section>
</template>

<script>

import PostPreview from '@/components/Posts/PostPreview'

export default {
    components: {
        PostPreview
    }
}

</script>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
