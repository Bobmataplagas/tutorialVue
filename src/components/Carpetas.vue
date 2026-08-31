<script setup lang="ts">
import imagen from '../assets/Carpetas.png'

</script>

<template>
<div>
<h2 class="text-center color1">Estructura de Carpetas o Archivos</h2>
</div>

<div class="color0 text-left">
    <p>Al generar un proyecto en Vue 3, se nos crea una estructura estándar de carpetas y archivos:</p>
</div>
<div class="color0 text-left">
    <ul>
      <li><strong>.vscode:</strong> Carpeta donde están las extensiones de vscode.</li>
      <li><strong>node_modules:</strong> Carpeta donde se están todas las dependencias y librerías de terceros necesarias para el proyecto.</li>
      <li><strong>public:</strong> Almacena archivos estáticos que no son procesados por el empaquetador.</li>
      <li><strong>src:</strong> Es el directorio principal de desarrollo donde está el código.
        <ul>
          <li><strong>assets:</strong> Contiene recursos estáticos como imágenes, fuentes, etc.</li>
          <li><strong>components:</strong> Aquí se guardan los componentes reutilizables de Vue.</li>
        </ul>
      </li>
      <li><strong>App.vue:</strong> Es la raíz de la aplicación; todos los demás componentes se anidan dentro de este para formar el programa.</li>
      <li><strong>main.ts:</strong> El archivo de entrada principal que inicializa la aplicación y la monta en el inspector o DOM.</li>
      <li><strong>index.html:</strong> Es la página de inicio del sitio web</li>
      <li><strong>package.json:</strong> Archivo de Node.js que contiene los metadatos del proyecto, scripts de ejecución y la lista de dependencias.</li>
      <li><strong>vite.config.js:</strong> Archivo de configuración para Vite, la herramienta de construcción por defecto en Vue 3.</li>
    </ul>
</div>
    <div class="image-center">
    <img :src="imagen" alt="Carpetas" style="padding-top: 3%;" width="15%">
    </div>
</template>

<style scoped>
</style>
