<template>
  <div class="appNavBar">
    <img src="/img/Logo.png" alt="Logo" class="logo" />
    <div class="menu">
      <NuxtLink to="/">
        <UButton
          icon="i-lucide-popcorn"
          variant="soft"
          class="menuButtonActive"
        >
          Explorar
        </UButton>
      </NuxtLink>
      <NuxtLink to="/my">
        <UButton
          icon="i-lucide-clapperboard"
          variant="soft"
          class="menuButton"
        >
          Meus filmes
        </UButton>
      </NuxtLink>
    </div>
    <div class="info">
      <div class="user">
        <p>Olá Jordan</p>
        <img src="/img/avatar.png" alt="Logo" class="avatar" />
      </div>
      <USeparator orientation="vertical" color="neutral" class="separator"></USeparator>
      <UButton icon="i-lucide-log-out" variant="soft" class="logoutButton">
      </UButton>
    </div>
  </div>
</template>

<script setup lang="ts">
import "~/assets/css/navBar.css";
</script>