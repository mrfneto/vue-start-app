<script setup>
import { useStore } from '../store'

const store = useStore()
</script>

<template>
  <h1 class="text-3xl font-bold underline">Welcome: {{ store.user.name }}</h1>
</template>
