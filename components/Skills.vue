<script lang="ts">
export default {
  data() {
    return {
      technologies: [
        {
          id: 1,
          technology: 'HTML',
          image: '/html.svg',
        },
        {
          id: 2,
          technology: 'CSS',
          image: '/css.svg',
        },
        {
          id: 3,
          technology: 'JavaScript',
          image: '/js.svg',
        },
        {
          id: 4,
          technology: 'TypeScript',
          image: '/typescript.svg',
        },
        {
          id: 5,
          technology: 'Vue',
          image: '/vue.svg',
        },
        {
          id: 6,
          technology: 'Nuxt',
          image: '/nuxt.svg',
        },
        {
          id: 7,
          technology: 'Git',
          image: '/git.svg',
        },
        {
          id: 8,
          technology: 'GitHub',
          image: '/github.svg',
        },
        {
          id: 9,
          technology: 'Linux',
          image: '/linux.svg',
        },
        {
          id: 10,
          technology: 'Webflow',
          image: '/webflow.svg',
        },
      ],
    }
  },
}
</script>

<template>
  <section id="skills" class="has-text-centered mt-6">
    <h1 class="is-primary is-size-2 is-size-1-tablet">Favourite tools and technologies</h1>
    <div class="container">
      <div class="grid">
        <MiniSkillsCard
        v-for="technology in technologies"
        :key="technology.id"
        :technology="technology.technology"
        :image="technology.image"
        class="column is-one-fifth m-3"
      />
      </div>

    </div>
  </section>
</template>
<style>
.grid{
  display:grid;
  grid-template-columns: repeat(2,1fr);
}

@media screen and (min-width:768px) {
.grid{
  display:grid;
  grid-template-columns: repeat(5,1fr);
}
}
</style>
