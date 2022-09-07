<script setup lang="ts">
const { data } = useFetch('https://api.chucknorris.io/jokes/random');
</script>
<template>
  <div>
    {{ data }}
  </div>
</template>
<style>
body {
  background-color: #000;
  color: #fff;
}
</style>
