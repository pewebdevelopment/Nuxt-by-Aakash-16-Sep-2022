<template>
  <div>
  <a href="#" @click="view('Home')">Home</a>
  <a href="#" @click="view('Counter')">Counter</a>

  <NuxtPage />
  
  <LazyHomeWelcome v-if="page === 'Home' " />
  <LazyCounter v-if="page === 'Counter' " />
</div>

</template>

<script setup>
  const page = ref('home');
  function view(name) {
    page.value = name;
  }
</script>