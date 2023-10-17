<template>
    <header>
        <HeaderNavigation />
    </header>
    <main class="container">
        <slot />
    </main>
</template>

<script setup lang="ts">
useHead({
  titleTemplate: (titleChunk) => {
    return titleChunk ? `${titleChunk} | Andrengineer` : 'Andrengineer';
  },
})
</script>