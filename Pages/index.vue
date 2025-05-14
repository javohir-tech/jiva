<script setup lang="ts">
useHead({
    title:"Home Page"
})
</script>
<template>
    <h1>hello nuxt</h1>
    <NuxtLink to="/about">about</NuxtLink> <br>
    <NuxtLink to="/user">user</NuxtLink>
</template>