<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Mybartop from './views/Mybartop.vue';
import Mycard from './views/Mycard.vue';
import Mybarlow from './views/Mybarlow.vue';
import HomeView from './views/HomeView.vue';
import Lastbar from './views/Lastbar.vue';


</script>

<template>
  <header>
    <Mybartop />
    <Mybarlow />
    <HomeView />
  </header>
  <main>
    <div className="grid-container">
      <Mycard />
    </div>
    <div classname="footer">
  <Lastbar />
</div>
  </main>
</template>

<style scoped>
.grid-container {
  display: grid;
  grid-column-gap: 0.9rem;
  grid-row-gap: 1.9rem;
}
@media (min-width: 400px) {
  .grid-container {
    grid-template-columns: repeat(1, 1fr);
  }
}
@media (min-width: 800px) {
  .grid-container {
    grid-template-columns: repeat(4, 1fr);
  }
}

</style>
