<script lang="ts">
export default {
  props: {
    service: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
    imagePath: {
      type: String,
      required: true,
    },
    imageDescription: {
      type: String,
      required: true,
    },
  },
}
</script>

<template>
  <div class="mini_card card">
    <div class="card-content">
      <div class="content">
        <img :src="imagePath" :alt="imageDescription" />
        <h5>{{ service }}</h5>
        <p>
          {{ description }}
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.mini_card {
  max-width: 350px;
}
.mini_card img {
  height:100px;
  width:100px;
  max-width: 100px;
  max-height: 100px;
}
</style>
