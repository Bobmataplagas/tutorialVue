<template>
    <header>
        <nav>
            <ul>
                <li><a href="#framework"> Framework </a></li>
                <li><a href="#requisitos"> Requisitos </a></li>
                <li><a href="#pasos"> Pasos </a></li>
                <li><a href="#carpetas"> Carpetas/Archivos </a></li>
                <li><a href="#componentes"> Componentes </a></li>
            </ul>
        </nav>
    </header>
</template>

<script lang="ts" setup>
</script>

<style scoped>
header {
  margin-bottom: 4%;
}

nav ul {
  display: flex;
  gap: 2%;
  justify-content: center;
  flex-wrap: wrap;
}

nav a {
  display: inline-block;
  padding: 10px 10px 10px;
  border: 1px solid rgba(255, 255, 255, 0.2);
  border-radius: 10px;
  background: rgba(255, 255, 255, 0.05);
  color: #fff;
  text-decoration: none;
  transition: all 0.2s ease;
  font-weight: 600;
}

nav a:hover {
  background: rgba(248, 5, 37, 0.459);
  border-color: rgba(255, 255, 255, 0.5);
  transform: translateY(-1px);
  box-shadow: 0 6px 16px rgba(125, 211, 252, 0.18);
}
</style>