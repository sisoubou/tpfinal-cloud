<script setup>
const buildId = import.meta.env.VITE_BUILD_ID ?? 'local'
const today = new Date().toLocaleDateString('fr-FR')
</script>
<template>
<header>
<p>Nom : Fadda</p>
<p>Prénom : Serena</p>
<p>Date : {{ today }}</p>
<p>Build : {{ buildId }}</p>
</header>
</template>