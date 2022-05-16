<template>
  <div class="jumbo">
      <img src="../assets/img/moon.jpeg" alt="moon">
  </div>
</template>

<script>
export default {
  name: "JumboHero",
};
</script>

<style scoped>
.jumbo {
    height: 35vh;
    width: 100%;
    margin-top: 2rem;
}

.jumbo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
}
</style>
