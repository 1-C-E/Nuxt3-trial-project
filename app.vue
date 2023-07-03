<template>
  <div class="app">
    <TheNavigation/>
    <div class="container">
      <NuxtPage/>
    </div>
    <TheFooter/>
  </div>
</template>

<style>
@import '@/assets/global.css';

.app {
  background-color: black;
}

.container {
  font-size: 70px;
  color: white;
  margin: 7rem 0 0 47rem;
}
</style>