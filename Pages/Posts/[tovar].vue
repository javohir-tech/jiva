<script setup lang="ts">
const route = useRoute()
</script>

<template>
    <div>
        tovar : {{ route.params.tovar }}
    </div>
</template>