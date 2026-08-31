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

  <section id="framework" class="seccion">
    <Framework />
  </section>

  <section id="requisitos" class="seccion">
    <Requisitos />
  </section>

  <section id="pasos" class="seccion">
    <Pasos />
  </section>

  <section id="carpetas" class="seccion">
    <Carpetas />
  </section>

  <section id="componentes" class="seccion">
    <Componente />
  </section>

  <div class="text-center color3">
  <h3>¡Gracias por su atención en este tutorial!</h3>
  <p><strong>Espero que este tutorial haya sido útil para aprender lo básico de Vue.js.</strong> </p>
  <p>_____________________________________________________________________________________________________________</p>
  </div>

  <img src="https://pic2-cdn.creality.com/crealityCloud/common/73d985700dec941d0f9e395469eee9fa.webp" alt="miku" class="img-corner0" width="10%" />
  <img src="https://longviewarboretum.org/wp-content/uploads/2026/04/flowersAsset-3@150x.webp" alt="flores" class="img-corner1" width="50%" />
  <img src="https://pbs.twimg.com/media/F0hsAuPagAABLeS.jpg" alt="aksually" class="img-corner2" width="5%" />
</template>
