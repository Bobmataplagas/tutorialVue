<script setup lang="ts">
import image from '../assets/componentes.png'
</script>

<template>
    <div>
    <h2 class="text-center color1">¿Qué es un componente en Vue?</h2>
    </div>

    <div class="color0 text-left">
        <p>Permite alternar fácilmente entre elementos dentro de una misma plantilla, lo que garantiza un código base más optimizado y fácil de mantener.</p>
        <p>Ofrecen una solución para modificar componentes durante la interacción del usuario, manteniendo la legibilidad del código dentro de la capa de presentación (etiquetas de plantilla).</p>
        <p>Cada componente encapsula su propio HTML (template), lógica (script) y estilos (CSS), generalmente dentro de un archivo con extensión .vue conocido como Single-File Component (SFC).</p>
    </div>

    <div class="image-center">
    <img :src="image" alt="Componentes" style="padding-top: 3%;" width="15%">
    </div>

</template>

<style scoped>

</style>
