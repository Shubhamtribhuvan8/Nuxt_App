<template>
    <div>
        <nuxt-link to="/search">Go to search</nuxt-link>
        <h1>Hello from page</h1>
        {{hello}}
    </div>
</template>
<script setup lang="ts">
  const hello='hello';
</script>
