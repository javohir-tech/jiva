<script setup lang="ts">
import AppButton from '~/Components/AppButton.vue';

useHead({
    title:"Home Page"
})
</script>
<template>
    <h1>hello nuxt</h1>
    <NuxtLink to="/about">about</NuxtLink> <br>
    <NuxtLink to="/user">user</NuxtLink><br>
    <AppButton>
        salom
    </AppButton> <br>
    <SharedButton/>
</template>