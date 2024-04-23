<template>
    <h1>About</h1>
    <h4>Nombre: {{ nombre }}</h4>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aspernatur excepturi mollitia inventore a voluptates cum aliquid veritatis, ipsum natus ex distinctio? Assumenda, iusto facilis. Magnam laudantium officia necessitatibus enim est?</p>
</template>
<script setup lang="ts">
    const route = useRoute()
    const nombre = route.params.nombre
</script>