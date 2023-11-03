<script setup>


</script>

<template>
  <header>
    <ol>
      <li><h1>coffee</h1></li>
      <li><h1>Tea</h1></li>
      <li><h1>Milk</h1></li>
      <li><h1>AAAAA</h1></li>
    </ol>
  </header>


</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
