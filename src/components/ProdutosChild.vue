<script setup>
import ButtonChild from './ButtonChild.vue';

defineProps(['id', 'nome', 'preco', 'categoria'])

</script>

<template>
  <li>
    ID: {{ id }} - {{ nome }} -R${{ preco }}, ({{ categoria }})
    <ButtonChild @clique="teste"> Corrigir preço</ButtonChild>
  </li>

</template>
<style scoped>

</style>
