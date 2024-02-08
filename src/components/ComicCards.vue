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
    <h5>{{ card.series }}</h5>
    <p>{{ card.type }}</p>
    <p>{{ card.price }}</p>
  </div>
</template>
<style>
.cards {
  img {
    aspect-ratio: 1;
    object-fit: cover;
    object-position: top;
  }
}
</style>
