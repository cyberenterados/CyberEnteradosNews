<script setup>
// Aquí importaremos después nuestras noticias
</script>

<template>
  <header class="header">
    <div class="container">
      <h1 class="brand">CyberEnterados<span>News</span></h1>
      <p class="tagline">Tecnología, Hardware y el mundo Linux</p>
    </div>
  </header>

  <main class="container">
    <div class="card">
      <h2>Próximamente: El setup de ManuExplora</h2>
      <p>Estamos configurando Lovelace para traerte las mejores noticias.</p>
    </div>
  </main>
</template>

<style scoped>
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
  text-align: center;
}

.brand {
  font-size: 3.5em;
  font-weight: 800;
  color: #646cff;
  margin-bottom: 0;
}

.brand span {
  color: #42b883; /* El verde de Vue */
}

.tagline {
  color: #888;
  font-style: italic;
}

.card {
  background: #1a1a1a;
  border-radius: 8px;
  padding: 2em;
  margin-top: 2rem;
  border: 1px solid #333;
}
</style>
