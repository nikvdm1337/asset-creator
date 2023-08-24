<script setup>
import SpHeader from './components/SpHeader.vue'
import FormSidebar from './components/FormSidebar.vue'
import HtmlOutput from './components/HtmlOutput.vue'
 


</script>

<template>
  <SpHeader />
  <main>
    <FormSidebar />
    <HtmlOutput />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
  color: black;
  background-color: #D03D12;
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
