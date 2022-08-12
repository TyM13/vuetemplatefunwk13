<template>
  <div>
<h1>{{blog_title}}</h1>
<p>{{blog_content}}</p>
<img :src="blog_image_url" alt="tower of appartments">

  </div>
</template>

<script>
  export default {
    
data() {
  return {
    blog_content: 'blog content',
    blog_title: 'blog title',
    blog_image_url: 'https://images.unsplash.com/photo-1660070918769-f34c724cfe43?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=685&q=80'
  }
},

  }
</script>

<style scoped>
</style>