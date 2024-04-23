<template>
    <h1>Su nombre es: {{ nombre }}</h1>
    <h4>Edad: {{ edad }}</h4>
</template>
<script setup lang="ts">
    const route = useRoute()
    const nombre = route.params.person
    const edad = route.params.edad
</script>