<template>
  <main class="explorar">
    <div class="explorarHeader">
      <h1 class="explorarTitle">Explorar</h1>
      <UInput icon="i-lucide-search" variant="outline" placeholder="Pesquisar filme" class="explorarBuscar" />
    </div>
    <section class="explorarListagem">
      <AppMovieCard />
    </section>
  </main>
</template>

<script setup lang="ts">
import "~/assets/css/listagemExplorar.css";
</script>