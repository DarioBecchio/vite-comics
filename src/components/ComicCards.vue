<script>
export default {
  name: "ComicCards",
  props: {
    card: Object,
  },
};
</script>
<template>
  <div class="cards">
    <img :src="card.thumb" alt="" />
    <h3>{{ card.series }}</h3>
    <p>{{ card.type }}</p>
    <p>{{ card.price }}</p>
  </div>
</template>
<style></style>
