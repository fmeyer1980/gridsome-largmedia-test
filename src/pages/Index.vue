<template>
  <Layout>
    
    <h1>Hello, world!</h1>
    <img src="../assets/images/hero.jpg?nf_resize=fit&w=100" alt="">
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores
    </p>

    <p class="home-links">
      <a href="https://gridsome.org/docs" target="_blank" rel="noopener">Gridsome Docs</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
