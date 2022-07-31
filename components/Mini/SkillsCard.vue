<script lang="ts">
export default {
  props: {
    technology: {
      type: String,
      required: true,
    },
    image: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
  },
}
</script>

<template>
  <div class="card skills_card">
    <div class="card-content">
      <div class="content">
        <img :src="image" :alt="description" />
        <p>{{ technology }}</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.skills_card {
  width: 9.5rem;
  height: 9.375rem;
  background-color: #f6f2fe;
}
img {
  height: 4.375rem;
  width: 6.25rem;
  max-width: 6.25rem;
  max-height: 6.25rem;
}

.skills_card:hover {
  box-shadow: 45px 52px 130px -39px rgba(87, 87, 87, 0.6);
  -webkit-box-shadow: 45px 52px 130px -39px rgba(87, 87, 87, 0.6);
  -moz-box-shadow: 45px 52px 130px -39px rgba(87, 87, 87, 0.6);
  background-color: white;
}
p {
  font-weight: bold;
}
</style>
