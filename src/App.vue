<script setup lang="ts">
import HeaderComponent from './components/HeaderComponent.vue'
import Framework from './components/Framework.vue'
import Requisitos from './components/Requisitos.vue'
import Pasos from './components/Pasos.vue'
import Carpetas from './components/Carpetas.vue'
import Componente from './components/Componente.vue'
</script>

<template>
  <h1 class="title-center color2">Tutorial de Vue.js</h1>
  <HeaderComponent />

  <div id="framework">
    <Framework />
  </div>

  <div id="requisitos">
    <Requisitos />
  </div>

  <div id="pasos">
    <Pasos />
  </div>

  <div id="carpetas">
    <Carpetas />
  </div>

  <div id="componentes">
    <Componente />
  </div>

  <h3 class="text-center color1">¡Gracias por su atención en este tutorial!</h3>
  <p>Espero que este tutorial haya sido útil para aprender lo básico de Vue.js.</p>
  <p>_</p>
</template>
