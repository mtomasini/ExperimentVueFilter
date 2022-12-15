<script setup>
import HelloWorld from './components/HelloWorld.vue'
import SearchBar from './components/SearchBar.vue';
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <h1 class="green">HELLO! Here's a list: </h1>
      <SearchBar />
    </div>
  </header>

</template>